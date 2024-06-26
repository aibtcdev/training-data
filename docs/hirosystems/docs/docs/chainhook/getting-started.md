---
title: Getting Started
custom_edit_url: null
---

Chainhook is a transaction indexing engine for Stacks and Bitcoin. It can extract data from blockchains based on a predicate definition. Chainhook can be used as a development tool and a service.

Chainhook can extract data from the Bitcoin and the Stacks blockchains using predicates (sometimes called `chainhooks`). A predicate specifies a rule applied as a filtering function on every block transaction.

- **Chainhook as a development tool** has a few convenient features designed to make developers as productive as possible by allowing them to iterate quickly in their local environments.
- **Chainhook as a service** can be used to evaluate new Bitcoin and/or Stacks blocks against your predicates. You can also dynamically register new predicates by [enabling predicates registration API](./guides/chainhook-as-a-service-stacks.md).

## Install Chainhook from source

Chainhook can be installed from the source by following the steps below:

1. Clone the [chainhook repo](https://github.com/hirosystems/chainhook/) by using the following command:

   ```bash
   git clone https://github.com/hirosystems/chainhook.git
   ```

2. Navigate to the root directory of the cloned repo:

   ```bash
   cd chainhook
   ```

3. Run cargo target to install chainhook:

   ```bash
   cargo chainhook-install
   ```

If you want to start using Chainhook for extracting data from Bitcoin or Stacks, you can design your predicates using the following guides:

- [How to use chainhooks with bitcoin](./guides/chainhooks-with-bitcoin.md)
- [How to use chainhooks with stacks](./guides/chainhooks-with-stacks.md)
