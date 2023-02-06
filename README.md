# vim-textobj-restful-request

## TL;DR

This plugin is designed to enhance operations or navigation for restful requests written in [rest.nvim](https://github.com/rest-nvim/rest.nvim) format by using text objects.

## Prerequisite

- [vim-textobj-user](https://github.com/kana/vim-textobj-user)
- [rest.nvim](https://github.com/rest-nvim/rest.nvim)

## Quick Start

### Text objects

The following text objects are provided:

- `ar`: Around the current request.
- `ir`: Inside the current request.

### Jump between requests

The default mappings are:

- `;j`: Jump to the beginning of the next request.
- `;k`: Jump to the beginning of the previous request, including the current one.
