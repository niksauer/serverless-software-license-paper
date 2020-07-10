# Serverless Software License

> Licenses are boring. Blockchains in vogue, and on everyone's lips.

This freely made up quote pretty much summarizes the attention both topics have received since Satoshi Nakamoto published his white paper on an electronic peer-to-peer network in 2008, shortly after which the first Bitcoins were mined, i.e. put into circulation. Both cryptocurrencies and the underlying blockchain technology have received much fanfare hereafter whereas licensing systems have practically remained the same.

Usually, licensing involves a backend system that keeps records on valid activation codes as well as who purchased them initially. If the license is lost, support may be contacted but that leaves edge cases such as using an abandoned software application. Furthermore, this type of licensing does not allow for aftermarket reselling as any change of ownership would have to be communicated to the application developer. Both of these problems are tackled by the solution proposed in this paper.

The basic idea is to replace traditional database records with tokens on the blockchain. Combined with the public key cryptography inherent to such systems, license ownership claims can be autonomously verified. All without requiring applications developers to setup and maintain their own infrastructure.

To begin, essential concepts of blockchain technology are presented. Then the new blockchain way of licensing is explained in detail, followed by a short overview of the development and validation techniques used to create a reference implementation consisting of the [token](https://github.com/niksauer/serverless-software-license) itself, a [JavaScript client library](https://github.com/niksauer/serverless-software-license) as well as an [Electron-based demo application](https://github.com/niksauer/serverless-software-license-example). The paper concludes by summarizing the efforts and outlining potential future research topics.

