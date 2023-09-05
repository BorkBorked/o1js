# o1js &nbsp; [![npm version](https://img.shields.io/npm/v/o1js.svg?style=flat)](https://www.npmjs.com/package/o1js) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/o1-labs/o1js/blob/main/CONTRIBUTING.md)

(O)1 Labs has renamed SnarkyJS to o1js, effective immediately!

This name change reflects the evolution of our vision for the premiere toolkit used by developers to build zero knowledge-enabled applications, while paying homage to our technology's recursive proof generation capabilities.

Your favorite functionality stays the same and transitioning to o1js is a quick and easy process:
- To update zkApp-cli, run the following command:
    `npm i -g zkapp-cli@latest`
- To remove the now-deprecated SnarkyJs package and install o1js, run the following command:
    `npm remove snarkyjs && npm install o1js`
- For existing zkApps, make sure to update your imports from `snarkyjs` to `o1js`
- No need to redeploy, you are good to go!

## o1js

o1js helps developers build apps powered by zero-knowledge (zk) cryptography.

The easiest way to write zk programs is using o1js.

o1js is a TypeScript library for [zk-SNARKs](https://minaprotocol.com/blog/what-are-zk-snarks) and zkApps. You can use o1js to write zk smart contracts based on zero-knowledge proofs for the Mina Protocol.

o1js is automatically included when you create a project using the [Mina zkApp CLI](https://github.com/o1-labs/zkapp-cli).

## Learn More

- To learn more about developing zkApps, see the [zkApp Developers](https://docs.minaprotocol.com/zkapps) docs.

- For guided steps building and using zkApps, see the [zkApp Developers Tutorials](https://docs.minaprotocol.com/zkapps/tutorials/hello-world).

- To meet other developers building zkApps with o1js, participate in the [#zkapps-developers](https://discord.com/channels/484437221055922177/915745847692636181) channel on Mina Protocol Discord.

- For a list of changes between versions, see the [CHANGELOG](https://github.com/o1-labs/o1js/blob/main/CHANGELOG.md).

- To stay up to date with o1js, see the [O(1) Labs Blog](https://blog.o1labs.org/tagged/o1js).

## Contributing

o1js is an open source project. We appreciate all community contributions to o1js!

See the [Contributing guidelines](https://github.com/o1-labs/o1js/blob/main/CONTRIBUTING.md) for ways you can contribute.

## Community Packages

High-quality community packages from open source developers are available for your project.

- **snarkyjs-elgamal** A partially homomorphic encryption library for o1js based on Elgamal encryption: [GitHub](https://github.com/Trivo25/snarkyjs-elgamal) and [npm](https://www.npmjs.com/package/snarkyjs-elgamal)

To include your package, see [Creating high-quality community packages](https://github.com/o1-labs/o1js/blob/main/CONTRIBUTING.md#creating-high-quality-community-packages).
