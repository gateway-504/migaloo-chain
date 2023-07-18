# Migaloo

![](https://user-images.githubusercontent.com/94062656/215557558-6d0c39f1-9405-439a-aeb5-9baccdbd9df8.png)

[![Go Report Card](https://goreportcard.com/badge/White-Whale-Defi-Platform/migaloo-chain)](https://goreportcard.com/report/White-Whale-Defi-Platform/migaloo-chain)

[![OpenSSF Best Practices](https://bestpractices.coreinfrastructure.org/projects/7139/badge)](https://bestpractices.coreinfrastructure.org/projects/7139)

Migaloo Chain adalah rumah bagi paus putih.

Chain ini bermula dari forknya wasmd, dan merupakan eksplorasi ke dalam template rantai berkemampuan CosmWasm yang lebih ketat mengikuti standar hulu. Ini dimulai sebagai repositori wasmd, dan kami berharap ini akan berakhir sebagai perhiasan/penyala/templat apa pun.
## Informasi Berguna

Testnet kami memiliki Alliance di dalamnya, tetapi mainnet kami tidak akan memiliki alliance sampai ada rilis yang lebih stabil dari <https://github.com/terra-money/alliance>.

Karena itu, percabangan seperti:

* `release/v1.0.x` adalah ujung cabang mainnet, dan mencerminkan status mainnet yang berfungsi hingga peluncuran v2
* `release/v2.0.x` adalah ujung cabang untuk v2, yang memungkinkan alliance.
* `release/v3.0.x` adalah cabang pengembangan saat ini, yang akan menambahkan kait osmosis ibc, async-icq, dan peningkatan ke ibc v7, sdk 47, cometbft 37, dan wasmd v0.40.0

## Sumber Sumber
CONTRIBUTING GUIDE]
1. [Website](https://migaloo.zone)
2. [LitePaper]() - Akan Datang
3. [Docs]( https://docs.migaloo.zone/) - Akan Datang
4. [Roadmap](./docs/ROADMAP.md)
5. [Discord](https://discord.com/channels/908044702794801233/1069611972053712947)
6. [Twitter](https://twitter.com/WhiteWhaleDefi)
7. [Telegram](https://t.me/whitewhaleofficial)

## Persyaratan Sistem 

* Sistem Operasi: Linux atau macOS
* Ruang disk: Setidaknya 100GB ruang bebas yang disarankan
* CPU: Multi-core processor, 4+ cores disarankan
* RAM: 8GB+ disarankan
* Jaringan: disarankan internet yang bagus

## Mulai cepat

Membutuhkan [Go 1.20](https://go.dev/doc/install) atau lebih tinggi.

```bash
make install
migalood version
```

## kontribusi

[PANDUAN KONTRIBUSI](./docs/CONTRIBUTING.md)

[Kode etik](./docs/CODE_OF_CONDUCT.md)

[Kebijakan dan Prosedur Keamanan](./docs/SECURITY.md)

[Lisensi](./LICENSE)

## Tau lebih banyak
* [Protokol White Whale](https://whitewhale.money/)
* [Dokumentasi Cosmos SDK](https://docs.cosmos.network/)
* [Tutorial Cosmos SDK](https://tutorials.cosmos.network/)

## Penafian

**Perangkat lunak Migaloo ditawarkan "sebagaimana adanya", dengan pemahaman bahwa pengguna menanggung semua risiko dan tidak ada jaminan atau jaminan yang diberikan.**
