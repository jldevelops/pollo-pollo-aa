# pollo-pollo-aa
AA to hold pollo pollo donated funds

https://testnetexplorer.obyte.org/#4a2VTBsJz94OLG5kio/+jzzPgO5p76y0AiwUnuN/KTc=

usage with `action` param, values:

`create` creates app (`producer`,`amount`,`stable`=1 if stable)

`withdraw` withdraws leftover bytes

`return` returns bytes from application (`id`,`addr`)

`donate` moves from donor account to application (`id`,`donor`)

`confirm` sends bytes to producer (`id`)

default case takes param `donor` and fills that account, could be called by anyone, all other methods only polloAddr()
