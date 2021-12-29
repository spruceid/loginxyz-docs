+++
title = "Quickstart"
weight = 1
sort_by = "weight"
insert_anchor_links = "right"
+++

# Getting Started
Sign-In with Ethereum (SIWE) is a direct authentication method that allows
key-based Ethereum accounts and signature-enabled smart contracts to
authenticate by signing a structured message. 

It is used by web services to establish authenticated sessions, providing a
more user-controlled alternative to today’s single sign-on services, which
largely rely on third party intermediaries such as Google and Facebook. SIWE is
flexible and can be used standalone, alongside other login methods, or to link
existing user accounts to Web3 via Ethereum addresses.

This tutorial will help you to get started with Sign-In with Ethereum beginning
with an end-to-end example project followed by quickstart instructions for
supported programming languages, web frameworks, and applications.

## Quickstart Example
This end-to-end example will help you understand how Sign-In with Ethereum
works, assuming some familiarity with developing full-stack JavaScript
applications.

1. Ensure that the latest `npm` is installed (`yarn` works as well), or install
   it if necessary.
```bash=
npm --version
```

2. Clone the SIWE repository, install dependencies, and run the example from
   the subdirectory.
```bash=
git clone https://github.com/spruceid/siwe
cd siwe/examples/notepad
npm install
npm run dev
```

3. Visit the example at http://localhost:4361 (or whichever port `npm`
   allocated). You will need a wallet, we recommend MetaMask. Additional
   wallets are supported, but you may need to register your application with
   them.

4. Try signing in with Ethereum and saving your note. Log out, and login
   again--you should see that the note was saved!
