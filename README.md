

# S32-Vape
- Vape Script [QBCORE]
- New QBCore

## Features
- Basic Config
- Low Resmon
- Item Vape

## Dependencies
- [qb-core](https://github.com/qbcore-framework/qb-core)

## Installation
### Manual
- Add the vape item image to `qb-inventory/html/images`
- Add the vape item to `qb-core/shared/items`
```
['vape'] 						 = { ['name'] = 'vape', 						['label'] = 'Vape', 					['weight'] = 100, 		['type'] = 'item', 		['image'] = 'vape.png',					['unique'] = true, 		['useable'] = true, 	['shouldClose'] = true, 	['combinable'] = nil, ['description'] = "Hmm", },
```
- Download the script and put it in the `[qb]` directory.
- Add the following code to your server.cfg/resouces.cfg
```
ensure rz-vape
```
