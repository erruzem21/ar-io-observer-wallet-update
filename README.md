<h1 align="center">Ar.io</h1>

## NODUNDA GATEWAY VE OBSERVER CÜZDANI FARKLI OLUP DA BURADA (https://api.arns.app/v1/contract/bLAgYxAdX2Ry-nt6aH2ixgvJXbpsEYm28NgJgyqfs-U/gateways) AYNI GÖRÜNENLER İÇİN. 
### (Nodeda gateway ile observer cüzdanı aynı olan bişey yapmasına gerek yok.)



KÜÇÜK BİR AYAR VE UPDATE YAPILMASI GEREK.


### Ve observer cüzdanınızda 0.1 - 1 Ar olması gerek

```console
cd ar-io-node/testnet-contract/tools
```
 içerisine girin
```console 
nano update-gateway-settings.ts
```
dosyayı açın


Aşağıdaki yerleri kendinize göre değiştirin. 

resimde görünen 'const observerWallet'  yerin önündeki // işaretlerini kaldırın resimdeki gibi ayarlayın.

diğeri ise aşağıdaki ''observerWallet,''  yazan yerin önündeki // işareterini kaldırın.

![image](https://github.com/erruzem21/ar-io-observer-wallet-update/blob/main/ar-io-observer.png)

Ctrl x y diyerek kaydedip çıkın.

```console
cd ..
```
ile bir önceki dizine geri gelin 
#### ar-io-node/testnet-contract  içinde olmasınız 
son olarak bunu çalıştırın. 
successfully alıp tx oluşacak.

```console
yarn ts-node tools/update-gateway-settings.ts
```

işlem bu kadar. üstteki siteden observer cüzdanınızın değiştiğini kontrol edin.

