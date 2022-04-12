# RecoMIDI Pre-Trained Model

***

## [NEW][Large/Stable]

### Here is a nice, large and stable model for RecoMIDI implementation. As always you have to "burn" a few samples before output would zero-in on a particular recommendation. 

### Download here:

```
!wget --no-check-certificate -O 'Morpheus-CLMP-Trained-Model.pth' "https://onedrive.live.com/download?cid=8A0D502FC99C608F&resid=8A0D502FC99C608F%2118557&authkey=ACG0zyLu5ENRhyU"

```

### You will need to set the following config in model loader:

```
config = GPTConfig(9300, 
                   1024,
                   dim_feedforward=1024,
                   n_layer=8, 
                   n_head=8, 
                   n_embd=1024,
                   enable_rpr=True,
                   er_len=1024)
```

### Enjoy!

***

### Project Los Angeles
### Tegridy Code 2022
