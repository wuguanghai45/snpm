snpm
=======
更改cnpm install 使它能适配spm install

## Install

```bash
git clone https://github.com/wuguanghai45/snpm.git
```
创建软连接到到node目录下
命令参考
```bash
ln -s /Users/admin/rails/snpm/bin/cnpm /Users/admin/.nvm/versions/node/v5.0.0/bin/snpm
```

## Usage
cd 到spm package.json 目录下
!注意 snpm install 是根据npm dependencies 进行下载
```bash
snpm install
```

