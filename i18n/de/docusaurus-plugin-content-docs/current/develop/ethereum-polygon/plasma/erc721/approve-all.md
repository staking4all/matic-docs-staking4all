---
id: approve-all
title: Alle freigeben
keywords:
- 'plasma client, erc721, approveAll, polygon, sdk'
description: 'Erste Schritte mit Maticjs'
---

# Freigeben {#approve}

Die `approveAll`-Methode kann angewandt werden, um alle Token freizugeben.

```
const erc721RootToken = plasmaClient.erc721(<root token address>, true);

const approveResult = await erc721RootToken.approveAll();

const txHash = await approveResult.getTransactionHash();

const txReceipt = await approveResult.getReceipt();

```
