# open5gs

![Version: 2.0.8](https://img.shields.io/badge/Version-2.0.8-informational?style=flat-square) ![AppVersion: 2.4.11](https://img.shields.io/badge/AppVersion-2.4.11-informational?style=flat-square)

Helm chart to deploy Open5gs services on Kubernetes.

**Homepage:** <https://github.com/gradiant/openverso-charts>

## Maintainers

| Name | Email | Url |
| ---- | ------ | --- |
| cgiraldo | <cgiraldo@gradiant.org> |  |

## Source Code

* <http://open5gs.org>

## Requirements

| Repository | Name | Version |
|------------|------|---------|
| file://../open5gs-amf | amf(open5gs-amf) | ~2.0.0 |
| file://../open5gs-ausf | ausf(open5gs-ausf) | ~2.0.0 |
| file://../open5gs-bsf | bsf(open5gs-bsf) | ~2.0.0 |
| file://../open5gs-hss | hss(open5gs-hss) | ~2.0.0 |
| file://../open5gs-mme | mme(open5gs-mme) | ~2.0.0 |
| file://../open5gs-nrf | nrf(open5gs-nrf) | ~2.0.0 |
| file://../open5gs-nssf | nssf(open5gs-nssf) | ~2.0.0 |
| file://../open5gs-pcf | pcf(open5gs-pcf) | ~2.0.0 |
| file://../open5gs-pcrf | pcrf(open5gs-pcrf) | ~2.0.0 |
| file://../open5gs-sgwc | sgwc(open5gs-sgwc) | ~2.0.0 |
| file://../open5gs-sgwu | sgwu(open5gs-sgwu) | ~2.0.0 |
| file://../open5gs-smf | smf(open5gs-smf) | ~2.0.0 |
| file://../open5gs-udm | udm(open5gs-udm) | ~2.0.0 |
| file://../open5gs-udr | udr(open5gs-udr) | ~2.0.0 |
| file://../open5gs-upf | upf(open5gs-upf) | ~2.0.0 |
| file://../open5gs-webui | webui(open5gs-webui) | ~2.0.0 |
| https://charts.bitnami.com/bitnami | common | 1.x.x |
| https://charts.bitnami.com/bitnami | mongodb | ~12.1.19 |

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| amf.enabled | bool | `true` |  |
| amf.image.tag | string | `"2.4.11"` |  |
| ausf.enabled | bool | `true` |  |
| ausf.image.tag | string | `"2.4.11"` |  |
| bsf.enabled | bool | `true` |  |
| bsf.image.tag | string | `"2.4.11"` |  |
| dbURI | string | `"mongodb://{{ .Release.Name }}-mongodb/open5gs"` |  |
| hss.enabled | bool | `true` |  |
| hss.image.tag | string | `"2.4.11"` |  |
| hss.mongodb.enabled | bool | `false` |  |
| mme.enabled | bool | `true` |  |
| mme.image.tag | string | `"2.4.11"` |  |
| mongodb.auth.enabled | bool | `false` |  |
| mongodb.enabled | bool | `true` |  |
| nrf.enabled | bool | `true` |  |
| nrf.image.tag | string | `"2.4.11"` |  |
| nssf.enabled | bool | `true` |  |
| nssf.image.tag | string | `"2.4.11"` |  |
| pcf.enabled | bool | `true` |  |
| pcf.image.tag | string | `"2.4.11"` |  |
| pcf.mongodb.enabled | bool | `false` |  |
| pcrf.enabled | bool | `true` |  |
| pcrf.image.tag | string | `"2.4.11"` |  |
| pcrf.mongodb.enabled | bool | `false` |  |
| populate.enabled | bool | `true` |  |
| populate.image.pullPolicy | string | `"IfNotPresent"` |  |
| populate.image.registry | string | `"docker.io"` |  |
| populate.image.repository | string | `"openverso/open5gs-dbctl"` |  |
| populate.image.tag | string | `"0.10.1"` |  |
| populate.initCommands | list | `[]` |  |
| sgwc.enabled | bool | `true` |  |
| sgwc.image.tag | string | `"2.4.11"` |  |
| sgwu.enabled | bool | `true` |  |
| sgwu.image.tag | string | `"2.4.11"` |  |
| smf.enabled | bool | `true` |  |
| smf.image.tag | string | `"2.4.11"` |  |
| udm.enabled | bool | `true` |  |
| udm.image.tag | string | `"2.4.11"` |  |
| udr.enabled | bool | `true` |  |
| udr.image.tag | string | `"2.4.11"` |  |
| udr.mongodb.enabled | bool | `false` |  |
| upf.enabled | bool | `true` |  |
| upf.image.tag | string | `"2.4.11"` |  |
| webui.enabled | bool | `true` |  |
| webui.image.tag | string | `"2.4.11"` |  |

----------------------------------------------
Autogenerated from chart metadata using [helm-docs v1.11.0](https://github.com/norwoodj/helm-docs/releases/v1.11.0)
"# ran" 
