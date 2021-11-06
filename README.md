# yere-yang-atilmasi-fix

> game/src/char_item.cpp

>Arat

```
bool CHARACTER::DropGold(int gold)
```
>Değiştir

```
bool CHARACTER::DropGold(int gold)
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
			# if curMoney <= 0:
			if curMoney >= 0:
				return
```
