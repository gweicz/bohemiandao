---
description: Ethereum sidechain, na kterém BohemianDAO běží
---

# xDai blockchain

**Jako blockchain, kde naše DAO smart-kontrakty provozujeme, byl zvolen** [**xDai**](https://www.xdaichain.com)**.**

Tento sidechain je plně _Ethereum-kompatibilní_ (můžete používat stejné peněženky a nástroje jako na Ethereu), velmi dostupný (levné a rychlé transakce) a dostatečně bezpečný. Nativní token, ve kterém se platí transakční poplatky, je [stablecoin](https://www.cryptopanda.cz/co-jsou-stablecoiny-a-jak-funguji/) [xDAI](https://www.coingecko.com/en/coins/xdai-stake) __ — tedy token odvozený od nejrozšířenějšího decentralizovaného stablecoinu [DAI](https://www.coingecko.com/en/coins/dai), který kopíruje cenu amerického dolaru ($). Mimochodem, tato síť je domovem pro [mnoho dalších DAO](https://app.daohaus.club/explore).

* xDai dokumentace: [https://www.xdaichain.com/](https://www.xdaichain.com)

![Logo xDai](../.gitbook/assets/xdai-logo.png)

{% hint style="info" %}
V budoucnosti se budeme poohlížet po migraci na druhou vrstvu Etherea (L2), např. v podobě tzv. [_rollupů_](https://medium.com/interdax/ethereum-l2-optimistic-and-zk-rollups-dffa58870c93), které nabídnou mnohem větší bezpečnost vložených prostředků.
{% endhint %}

## Jak získat xDAI na transakční poplatky?

Možností jak získat xDAI token je několik:

* Využijte tzv. faucet, kde můžete získat 0.1 xDAI zdarma - [odkaz na faucet](https://blockscout.com/xdai/mainnet/faucet)
* Převeďte si DAI z Ethereum blockchainu na XDai Chain pomocí [xDai Bridge](https://bridge.xdaichain.com)
* Požádejte o xDAI na [Gwei.cz Discord chatu](https://chat.gwei.cz)

## Převod Etheru (ETH) na xDai

K tomu, abyste se mohli stát členy, nebo zvýšit svůj podíl, potřebujete do DAO vložit nějaký ETH (Ether). Nicméně, převést ETH na xDai blockchain není úplně jednoduché a levné. Následuje popis aktuálně dostupných možností.

{% hint style="info" %}
Na xDai chain není možné dostat přímo Ether (ETH) jako takový, ale jen jeho ERC-20 kompatibilní verze [WETH](https://weth.io).
{% endhint %}

### 1) Využití xDai OmniBridge

* Transakční náklady: $60 - $300
* Rychlost: do 30 minut

Tahle možnost je nejrychlejší a nemusíte důvěřovat žádným třetím stranám, ale je také zdaleka nejdražší, co se týče transakčních poplatků. Bohužel v současné době není OmniBridge na převod Etheru příliš optimalizovaný a tak transakční poplatek vyjde cca na 180 tisíc jednotek gasu (při ceně gasu 150 gwei a ceně ETH cca $4000 je to cca $115 poplatek). Navíc si ještě musíte připočítat poplatek pro wrap ETH do WETH a schvalovací transakci.

#### Postup převodu ETH na xDai chain pomocí OmniBridge

1. Pokud máte ETH, musíte ho wrapnout na WETH, např. pomocí [Uniswap rozhraní](https://swap.elena.finance/#/swap?inputCurrency=\&outputCurrency=0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2)
2. Jděte do stránku OmniBridge - [https://omni.xdaichain.com/bridge](https://omni.xdaichain.com/bridge)
   1. Připojte svojí peněženku
   2. Jako výchozí token zvolte WETH
   3. Zadejte WETH částku kterou chcete převést
   4. Odešlete schvalovací transakci tlačítkem "Unlock"
   5. Zahajte převod stisknutím tlačítka "Transfer"
3. Hotovo, po pár minutách je váš WETH převedený na xDai chain

### 2) Směna P2P v rámci komunity (doporučujeme!)

* Transakční náklady: $5 - $30
* Rychlost: pár minut až několik dní - dle domluvy

Jelikož je zbytečné ztratit desítky či stovky dolarů na transakčních poplatcích, které se dají využít v rámci DAO mnohem lépe, tak nabízíme možnost směny P2P (_z ruky do ruky_) v rámci naší komunity. Transakční náklady budou tak naprosto minimální, protože z vaší strany půjde jen o klasický ETH transfer.

#### Důvěryhodní lidé, kteří můžou zprostředkovat směnu

| Jméno    | [Discord](https://chat.gwei.cz) | [Fórum](https://forum.gwei.cz)       | Keybase                         | Email                                   | ETH adresa                                                        |
| -------- | ------------------------------- | ------------------------------------ | ------------------------------- | --------------------------------------- | ----------------------------------------------------------------- |
| **tree** | tree#7466                       | [tree](https://forum.gwei.cz/u/tree) | [tree](https://keybase.io/tree) | [tree@hidden.cz](mailto:tree@hidden.cz) | [treecz.gweicz.eth](https://etherscan.io/address/tree.gweicz.eth) |

#### Postup pro P2P směnu

1. Kontaktujte vybraného zprostředkovatele (viz tabulka výše) a uveďte tyto údaje:
   1. částku, kterou chcete převést
   2. zdrojovou adresu, z které budete prostředky zasílat (pokud budete peníze zasílat z centralizované burzy je nutné to uvést!)
   3. cílovou adresu na které chcete prostředky na xDai Chain obdržet
2. Vyčkejte na odpověď, zda je možné převod provést
3. Po potvrzení zašlete ETH či WETH na zadanou adresu (zkontrolujte zda adresa sedí, viz. tabulka výše!)
4. Zprostředkovatel vám zašle WETH na xDai chain

{% hint style="warning" %}
Vždy si zkontrolujte zda komunikujete se správným člověkem (viz tabulka výše)! Peníze zasílejte jen na adresy uvedené v tabulce!\
(Například na Discordu si zkontrolujte nejenom jméno, ale i tzv. handle, tedy číslo za přezdívkou!).
{% endhint %}

### 3) Alternativní cesta přes DAI stablecoin

Další, ale už mnohem komplikovanější možnost jak získat WETH na xDai chainu je využít místní decentralizovanou burzu [HoneySwap](https://honeyswap.org) (lokální klon Uniswapu) - tedy obstaráte si nějakým způsobem xDAI (viz možnosti níže) a směníte ho na WETH. Tato možnost je jen pro zkušené uživatele a rozhodně ji nedoporučujeme nováčkům.

Tady je pár možností jak získat větší obnos xDAI:

* Pokud máte DAI na Ethereum síti, pak je možné převést ho pomocí [xDai Bridge](https://bridge.xdaichain.com), který je mnohonásobně levnější než OmniBridge
* Směnit USDT na xDAI na centralizované burze [AscendEX](https://ascendex.com/en/basic/cashtrade-spottrading/usdt/xdai)
* Nakoupit xDAI přímo za fiat pomocí směnáren [Ramp.Network](https://ramp.network/buy/?swapAsset=XDAI) nebo [Mt Pelerin](https://www.mtpelerin.com/buy-xdai#)

