{% if page.codename != "jackpot2lte" %}
{% if page.codename == "jackpotlte" %}
## 2026-08-28
- fix a typo in partition sizes that made the build unflashable
{% endif %}

## 2026-08-27
{% if page.codename == "jackpotlte" %}
- correct partition sizes for A530N
{% endif %}
- fix OTA for future builds (this build still has to be flashed manually)

## 2026-08-25
{% if page.codename == "a7y18lte" %}
- setup SKUs for models with NFC (resolves NFC crashes on non-NFC models potentially causing battery drain and heat)
{% endif %}
- declare support for mifare tags
- resolve some selinux denials

## 2026-08-22
- initial release build  
  
  Changes since 20260816 test build:  
  - enable CONFIG_USB_CONFIGFS_MASS_STORAGE in defconfig
  - uncomment c2.android.vp9.encoder entry from media config (since we have it available now)
{% endif %}
