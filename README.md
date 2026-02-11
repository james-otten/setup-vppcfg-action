# Setup vppcfg Action

Setup a specified version of [vppcfg](https://git.ipng.ch/ipng/vppcfg).

## Usage

```
    - name: Install vppcfg
      uses: setup-vppcfg-action@main
      with:
        install-source: "pypi"
        vppcfg-ver: "1.1.0"
```

## Options

| Input  | Description | Required |
| :---       |     :---     |    :---:   |
| `install-source` | Location to install vppcfg from. Either `pypi` or `source`. Default `pypi` | Required
| `vppcfg-ver` | Version of vppcfg to install when `install-source` is `pypi`. Default `1.1.0` | Optional
| `vppcfg-ref` | Ref of vppcfg to install when `install-source` is `source`. Default `main` | Optional
