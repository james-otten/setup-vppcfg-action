# Setup vppcfg Action

Setup a specified version of [vppcfg](https://git.ipng.ch/ipng/vppcfg).

## Usage

```
    - name: Install vppcfg
      uses: setup-vppcfg-action@main
      with:
        vppcfg-ref: "main"
```

## Options

| Input  | Description | Required |
| :---       |     :---     |    :---:   |
| `vppcfg-ref` | Ref of vppcfg to install. Default `main` | Optional
