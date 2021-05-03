<div align='center'><br /><img src="https://raw.githubusercontent.com/theia-ide/security-audit/master/assets/security-header.png" width="400px"/></div>

### Security Audit - 3/5/2021 at 0:57 UTC
-- -

#### Scan Summary

| Moderate | High | Critical |
|:---|:---|:---|
| 3 | 2 | 0 |


#### Scan Details

| Security Vulnerability | Module Name | Severity | Version | Vulnerable Versions | Patched Versions | Recommendation | Path |
|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|
| [Code Injection](https://npmjs.com/advisories/813) | js-yaml (dependency) | high | 3.7.0 | <3.13.1 | >=3.13.1 | Upgrade to version 3.13.1. | @theia/cli>@theia/application-manager>css-loader>cssnano>postcss-svgo>svgo>js-yaml |
| [Remote Code Execution](https://npmjs.com/advisories/1548) | serialize-javascript (dependency) | high | 1.9.1 | <3.1.0 | >=3.1.0 | Upgrade to version 3.1.0 or later. | @theia/cli>@theia/application-manager>@theia/compression-webpack-plugin>serialize-javascript |
| [Regular Expression Denial of Service](https://npmjs.com/advisories/565) | ssri (dependency) | moderate | 5.3.0 | >=5.2.2 <6.0.2 \|\| >=7.0.0 <8.0.1 | >=6.0.2 <7.0.0 \|\| >=8.0.1 | Update to version 6.0.2 or 8.0.1 or later | @theia/cli>@theia/application-manager>copy-webpack-plugin>cacache>ssri |
| [Denial of Service](https://npmjs.com/advisories/788) | js-yaml (dependency) | moderate | 3.7.0 | <3.13.0 | >=3.13.0 | Upgrade to version 3.13.0. | @theia/cli>@theia/application-manager>css-loader>cssnano>postcss-svgo>svgo>js-yaml |
| [Cross-Site Scripting](https://npmjs.com/advisories/1426) | serialize-javascript (dependency) | moderate | 1.9.1 | <2.1.1 | >=2.1.1 | Upgrade to version 2.1.1 or later. | @theia/cli>@theia/application-manager>@theia/compression-webpack-plugin>serialize-javascript |

