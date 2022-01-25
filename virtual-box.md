# VirtualBox

## Поменять UUID образа диска для клонирования

```shell
VBoxManage internalcommands sethduuid "C:\_VMs\SC9u1\sc9u1.vdi"
```

## Уменьшить размер образа диска

```shell
sdelete.exe -s -z С:
VboxManage.exe modifyhd "D:\Oracle VM VirtualBox\Windows 10 x86 Ent 1607.vdi" --compact
```
