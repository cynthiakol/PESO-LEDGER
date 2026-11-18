# Peso Ledger

A personal finance desktop app: salary, expenses, transfers, savings, investments and debts.
You enter everything by hand. It does not connect to Maya, GCash or any bank.
Data is stored locally on your computer.

## Run it locally
1. Install Node.js 20 or newer.
2. `npm install`
3. `npm start`

## Publish an installer on GitHub
1. Create an empty repository on GitHub and push this folder to it.
2. Tag a release and push the tag:
   `git tag v1.0.0` then `git push origin v1.0.0`
3. The Release workflow builds the Windows installer and attaches
   `PesoLedger-Setup-1.0.0.exe` to a draft release under the repository's Releases page.
   Open it and click Publish release.
4. To ship an update, raise "version" in package.json, commit, and push a new tag (for example v1.0.1).

Windows SmartScreen may warn about an unsigned app. Choose More info, then Run anyway.

## Your data
Records live in the app's local storage inside your Windows user profile.
Use Settings, then Export backup, from time to time and keep the file somewhere safe.
