# yere-yang-atilmasi-fix

> game/src/char_item.cpp

>Arat

```
bool CHARACTER::DropGold(int gold)
```
>Değiştir

```
bool CHARACTER::DropGold(int gold) // @fixmeka040
{
	return false;
}
```
> root/uiinventory.py

>Arat:

```
			if curMoney <= 0:
```
>Değiştir

```
			# if curMoney <= 0: # @fixmeka040
			if curMoney:
				return
```
