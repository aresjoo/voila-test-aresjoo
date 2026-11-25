# 결제 로고 원본

기존 Stripe/브랜드 원본을 assets/pay에서 옮겼다. 새 JCB, USDT, USDC도 아래 공식 배포 파일의 바이트 그대로다. archive_member는 압축파일 안 원본 경로. Apple/Google 간편결제는 제공자 연결 전이라 노출하지 않는다.

- visa.png: https://cdn.visa.com/v2/assets/images/logos/visa/blue/logo.png
  SHA256 0ebb1697ec9ed895955069d5aca347918d92cd59da740f98f772f468707e2361
- amex-mastercard-visa.svg: https://www.americanexpress.com/content/dam/amex/us/merchant/supplies-uplift/product/digital/CHECKOUT1IT.zip / CHECKOUT1IT/Amex_MasterCard_Visa/3_Card_color_horizontal.svg
  SHA256 4829e6fcc8fd5a65ffdadfb0beee7b2ecab759b95d0300f9880ff32a18d872cd
- visa-stripe.svg: https://js.stripe.com/v3/fingerprinted/img/visa-729c05c240c4bdb47b03ac81d9945bfe.svg
  SHA256 d0b63ce61a6e0367ae657102f479f114fa8851a0e95d1894971dd5cddb426725
- mastercard-stripe.svg: https://js.stripe.com/v3/fingerprinted/img/mastercard-4d8844094130711885b5e41b28c9848f.svg
  SHA256 747fca640bc3ae35c7422e023f27cf4a0953b7fe694bfb8bb528b50b70bd15ce
- amex-stripe.svg: https://js.stripe.com/v3/fingerprinted/img/amex-a49b82f46c5cd6a96a6e418a6ca1717c.svg
  SHA256 07483f00631032dfd02e79d3de16d990830ec530b691c236b58a641b4b752458
- discover-stripe.svg: https://js.stripe.com/v3/fingerprinted/img/discover-e5b11bba2aa760e805fba9f98e5c6581.svg
  SHA256 52c8feb24f0b8dfb959df93bbf1750f43407049131f58dece6ae4ee8cc5e5431
- unionpay-stripe.svg: https://js.stripe.com/v3/fingerprinted/img/unionpay-8a10aefc7295216c338ba4e1224627a1.svg (52쪽, 유니온페이 번호를 알아보면 이 하나만)
  SHA256 3cd41a77ef3c37c2affe67c940b630dd8f96a16b6e56158088f796a0e62476b9
- cvc-stripe.svg: https://js.stripe.com/v3/fingerprinted/js/elements-inner-payment-afa6530aa25c717ba0f8db567497e674.js
  SHA256 fe6d5c2deb5708a38fca290b8f866683905eb6dc5c01903873a3febc1f6cf566
- jcb.gif: https://jcb.sitecorecontenthub.cloud/api/public/content/105660_pic_logo_01.gif
  SHA256 f1a11d8de636ca11d7452bf37f9d948df4505aaf8fa29d4c116c7b2d80815669
- usdt.svg: https://tether.to/images/logoCircle.svg
  SHA256 7c9f13b068996186c4df0f3dcdeeeb86e11cee6d8a9e7597cec19ccee164d7c5
- usdc.svg: https://6778953.fs1.hubspotusercontent-na1.net/hubfs/6778953/Pressroom/brandkit/logo-downloads/usdc.zip / Token Logo/USDC Token.svg
  SHA256 fe4f9d5f34ef4ebeb5d80e1f5ff63dcaf5a0d5495f4adf206e4c3011d1f5c57d

## #po-618 네트워크 원본

- bep20.svg: https://www.bnbchain.org/images/brand-guidelines/svg/BNB%20Chain_Symbol_Yellow.svg
  SHA256 b8ff1ce0b5af2e2d9bcf5ec89fedd5224079f4f7267e306e23e8d691024f5eff
- erc20.png: https://raw.githubusercontent.com/ethereum/ethereum-org-website/dev/public/images/assets/eth-diamond-purple.png
  SHA256 9eb3a3787b884a9886859dd8ab2cb8d2b2c4f19c0c4d6f7f199dc2defa404fcd

TRON 공식 resources의 로고 ZIP은 이 환경에서403을 반환했다. 원본을 얻지 못한 TRON, Bitcoin, XRP 표식은 비워 둔다. 임의 표식을 그리지 않았다.

## #po-670 BTC, TRX, XRP

세 파일은 아래 배포 원본의 바이트 그대로다. SVG 재작성과 색 변환 없음. TRON은 trondao.org가 연결한 브랜드 키트의 다운로드 파일이다.

- btc.svg: https://raw.githubusercontent.com/bitpay/bitcoin-brand/887f040f7c44660b84c4000f4a54897ba5518194/bitcoin.svg
  출처: https://github.com/bitpay/bitcoin-brand
  SHA256 3672ebaa9a2c6e7490636c8f3fc093ed1601f9aca103f164a6926cd1a5488d77
- trx.svg: https://drive.google.com/uc?export=download&id=17i5w5DnH-9WU7aG8Q4bnRwKPUVjg-HIq
  출처: https://trondao.org/
  브랜드 키트: https://tronbrandkit.figma.site/
  압축 원본: Logo Icon SVG/TRON LOGO ICON WHITE.svg
  SHA256 1275458269a8d696eec8f511e03aec132e0cc6bfc22e0353c9106c24c9616906
- xrp.svg: https://xrpl.org/XRPL_Brand_Kit.zip
  출처: https://xrpl.org/about/xrp
  압축 원본: XRP Brand Design System/1. XRPL Logo Kit/svg/Symbol/XRP Ledger - Symbol - White.svg
  SHA256 22b041ad0b656398916a62f720673964a58071c55b9281f8fe6a3727732d6b89
