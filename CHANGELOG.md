# Changelog

<!--next-version-placeholder-->

## v1.25.5 (2022-04-28)
### Fix
* Catch ServerDisconnectedError ([`e921bfa`](https://gitlab.com/keatontaylor/alexapy/-/commit/e921bfa607a1cf6714bcffbc01f2ed3f8916ca5c))
* Loosen cryptography requirement ([`b1e6178`](https://gitlab.com/keatontaylor/alexapy/-/commit/b1e617867f29a952cb4b91e7260307488d28fec7))

### Documentation
* Rebuild sphinx docs ([`739318c`](https://gitlab.com/keatontaylor/alexapy/-/commit/739318cc0a24bf9361b31f5ac8105e3e5e5d71ca))

## v1.25.4 (2022-02-25)
### Fix
* Bump dependencies ([`6dc1dfa`](https://gitlab.com/keatontaylor/alexapy/-/commit/6dc1dfa127ab38e5e2b29861195344c16dda45e1))

## v1.25.3 (2021-11-23)
### Fix
* Bump authcaptureproxy ([`e125e0d`](https://gitlab.com/keatontaylor/alexapy/-/commit/e125e0d21d4bfdd2533ee6d304a872a7bd3035aa))
* Update authcaptureproxy ([`b79f0a3`](https://gitlab.com/keatontaylor/alexapy/-/commit/b79f0a311084f32dd5686bfae7b1a96d6b8ccc5b))
* Update aiohttp to 3.8.1 ([`eed0735`](https://gitlab.com/keatontaylor/alexapy/-/commit/eed07351389237933de542e79f4465dc5817bc64))

## v1.25.2 (2021-11-16)
### Fix
* Swap to protocol A:F for websocket ([`baf9f7d`](https://gitlab.com/keatontaylor/alexapy/-/commit/baf9f7dc4eb252e9bd460ba26d294a72f041d53a))

## v1.25.1 (2021-05-01)
### Fix
* Handle pyotp missing TOTP attribute ([`2ac97bc`](https://gitlab.com/keatontaylor/alexapy/-/commit/2ac97bc13080b436d36b1559817c152c4b85164d))

## v1.25.0 (2021-04-12)
### Feature
* Add methods for device discovery and light control ([`a43f4b3`](https://gitlab.com/keatontaylor/alexapy/-/commit/a43f4b3a0aea8fd062c5908a747deda6f8cdab57))

## v1.24.5 (2021-03-16)
### Fix
* Bump authcaptureproxy to 0.7.0 ([`3c8839f`](https://gitlab.com/keatontaylor/alexapy/-/commit/3c8839fff00e246df6fab7fbea06902a7e3b9211))

## v1.24.4 (2021-03-12)
### Fix
* Catch json decode errors ([`dbee4aa`](https://gitlab.com/keatontaylor/alexapy/-/commit/dbee4aa63256fd2e66078ad650d335734902d37c))

## v1.24.3 (2021-03-11)
### Fix
* Get summary for audio books ([`f26540e`](https://gitlab.com/keatontaylor/alexapy/-/commit/f26540ec8467c53ec0333c2c9f7dfb614570453d))

## v1.24.2 (2021-02-20)
### Fix
* Correct version number ([`cdd3d94`](https://gitlab.com/keatontaylor/alexapy/-/commit/cdd3d9409bdbace26016ece7645358224759c76d))

### Documentation
* Fix spelling in description ([`3756038`](https://gitlab.com/keatontaylor/alexapy/-/commit/3756038e1bd4edc8b77b760a240e87754aab674d))

## v1.24.1 (2021-02-15)
### Fix
* Populate more metadata for package ([`d6f3cc6`](https://gitlab.com/keatontaylor/alexapy/-/commit/d6f3cc68b0b82828078dc1dc223be340b9c274f4))

### Documentation
* Add readthedocs link ([`2a0978d`](https://gitlab.com/keatontaylor/alexapy/-/commit/2a0978d638b777ba1a98836a29299e122f1b8136))
* Add sphinx document generation ([`8935a3b`](https://gitlab.com/keatontaylor/alexapy/-/commit/8935a3b8d53c11138fa58f0c747ace6f9adff542))
* Update badges ([`1485f72`](https://gitlab.com/keatontaylor/alexapy/-/commit/1485f72e456a53ef41705cfd561fa16f9252f964))
* Add download badges ([`02fdd87`](https://gitlab.com/keatontaylor/alexapy/-/commit/02fdd87542a91396910532325b77b78b7712b266))
* Add pypi download badge ([`283703f`](https://gitlab.com/keatontaylor/alexapy/-/commit/283703f11caa06d41fdf231c869a1979ad80eaa7))

## v1.24.0 (2021-02-08)
### Feature
* Add change_login function ([`0e1147b`](https://gitlab.com/keatontaylor/alexapy/-/commit/0e1147bfaeaf2c8acfe76925c627603351b54c7d))

### Fix
* Remove modifier clear from test ([`bd59728`](https://gitlab.com/keatontaylor/alexapy/-/commit/bd597281ce6a6e9d55b35d3b5cac17c9accb11c7))

## v1.23.1 (2021-02-07)
### Fix
* Allow reuse of alexaproxy ([`4c2b5a0`](https://gitlab.com/keatontaylor/alexapy/-/commit/4c2b5a096a7ccbbd932bb830faff6c3b237ee9e6))
* Fix autofill to only fill in blank values ([`95cbbd3`](https://gitlab.com/keatontaylor/alexapy/-/commit/95cbbd3b3c46971a0b1bf15b0b3197aa2cba8043))

## v1.23.0 (2021-02-06)
### Feature
* Update deps ([`a00ba4d`](https://gitlab.com/keatontaylor/alexapy/-/commit/a00ba4df5f26ad2b665ff9a0f0153c43e41ac79f))

## v1.22.3 (2021-01-28)
### Fix
* Update to v2 automation url ([`17cc499`](https://gitlab.com/keatontaylor/alexapy/-/commit/17cc49953ccdb2ab7ca280da3a8954626a63b124))

## v1.22.2 (2021-01-23)
### Fix
* Fix test for stored email for non-email login ([`02f5f9c`](https://gitlab.com/keatontaylor/alexapy/-/commit/02f5f9c0d8437b7c39e12b4f71e3a5c8cd8f3a80))
* Use proper start url on forgotpassword ([`9f5fa64`](https://gitlab.com/keatontaylor/alexapy/-/commit/9f5fa6488f2e42f72da13215a6fd38469e56ada4))
* Handle site redirection if headers blank ([`5395ac5`](https://gitlab.com/keatontaylor/alexapy/-/commit/5395ac599972ab6ade214d89a6726c6e0d3a296b))

## v1.22.1 (2021-01-23)
### Fix
* Add fallback to amazon.com ([`0968f71`](https://gitlab.com/keatontaylor/alexapy/-/commit/0968f7132b7eeeaeb36f049bf7c5a9977bc3a440))
* Handle empty response from activities ([`bb643a7`](https://gitlab.com/keatontaylor/alexapy/-/commit/bb643a7cd00c8b16ae6c821d2468af676d9d4fcd))
* Downgrade if oauth token refresh fails ([`0296314`](https://gitlab.com/keatontaylor/alexapy/-/commit/0296314566cab0038c7e27671bbc859132c9d455))

## v1.22.0 (2021-01-18)
### Feature
* Add summary for get_last_device_serial ([`887f689`](https://gitlab.com/keatontaylor/alexapy/-/commit/887f689b96997bedfc3f43791d2800dc7f083623))
* Autofill otp for proxy if available ([`6113132`](https://gitlab.com/keatontaylor/alexapy/-/commit/6113132fc7b9526da32e42ce2573f44d81de5812))

### Fix
* Ignore skill invocations with last_called ([`92a35fe`](https://gitlab.com/keatontaylor/alexapy/-/commit/92a35fe72f068575fa41e257f53de58bb96c8f9a))
* Add oauth_login option ([`2a79d69`](https://gitlab.com/keatontaylor/alexapy/-/commit/2a79d69c501796363403a7004c19d810dec1e263))
* Use device serial number instead of unique_id ([`cf558bd`](https://gitlab.com/keatontaylor/alexapy/-/commit/cf558bda21c786b4b7abca1478afdb08eca44e3f))
* Fix TypeError when login not determined ([`71b5941`](https://gitlab.com/keatontaylor/alexapy/-/commit/71b594159288cc1df510a459bcfc1839f1650333))
* Fix language for .es domain to Spanish ([`bd068d3`](https://gitlab.com/keatontaylor/alexapy/-/commit/bd068d305ba4ee5c6455be9c32b4f50b10afd31c))
* Generate cookiefile path dynamically ([`f57ee13`](https://gitlab.com/keatontaylor/alexapy/-/commit/f57ee1337f22d083e5f5d782f2e8380189f0efc6))
* Collect email/password in earlier post ([`0508732`](https://gitlab.com/keatontaylor/alexapy/-/commit/0508732a8f56e629c9351450be56a1376b37b26d))
* Fix premature submission for action_required ([`c529554`](https://gitlab.com/keatontaylor/alexapy/-/commit/c52955404ac226d951cbcf4c6a0e37462b212335))
* Handle connection errors ([`659cf9f`](https://gitlab.com/keatontaylor/alexapy/-/commit/659cf9f53e11c58f323ec57b0be579935dbc5601))

## v1.21.0 (2021-01-09)
### Feature
* Enable proxy login option ([`66ae83c`](https://gitlab.com/keatontaylor/alexapy/-/commit/66ae83cd38e54eb66d015cc075f9513c8f8eccf9))

### Fix
* Provide get request parameters ([`8bc47c0`](https://gitlab.com/keatontaylor/alexapy/-/commit/8bc47c08a3d8371daa38e39809437b3c224a22b2))

## v1.20.5 (2021-01-08)
### Fix
* Fix registration error with amazon.com.au ([`690f99a`](https://gitlab.com/keatontaylor/alexapy/-/commit/690f99a58eb91f4d3e2e6824453e8511a7bd07a4))

## v1.20.4 (2021-01-06)
### Fix
* Accept .domain cookies ([`1a496c0`](https://gitlab.com/keatontaylor/alexapy/-/commit/1a496c0e635e8211e73a27f5f8b242bf89d2d2e7))
* Save cookiefile after non-.com login ([`8704eae`](https://gitlab.com/keatontaylor/alexapy/-/commit/8704eaeae79f713f13509beb968e05a8c831dc34))
* Add domain to cookies from exchange ([`6a1f616`](https://gitlab.com/keatontaylor/alexapy/-/commit/6a1f616ff77d46c42f791f2fada0f19b42ece8da))
* Fix typo in debug message ([`056670e`](https://gitlab.com/keatontaylor/alexapy/-/commit/056670e81490bbac0d04c17c45fea4869d9319ca))
* Increment api_calls on static calls ([`ea70527`](https://gitlab.com/keatontaylor/alexapy/-/commit/ea70527cdd393e9d041ced902df267ef2357ecf5))
* Fix return for oauth functions ([`d8cc629`](https://gitlab.com/keatontaylor/alexapy/-/commit/d8cc6297589b3f9268a1b3b6872fc0ceeae88483))

## v1.20.3 (2021-01-02)
### Fix
* Add languages for oauth login ([`c0803c5`](https://gitlab.com/keatontaylor/alexapy/-/commit/c0803c5e828524ea8965a9842c8c7d0354d34c24))
* Fix deviceid generation for logins ([`73747dc`](https://gitlab.com/keatontaylor/alexapy/-/commit/73747dca1850f1c25a0ca70ad721e6957072e601))
* Fix app name ([`a75211f`](https://gitlab.com/keatontaylor/alexapy/-/commit/a75211fadd5bc8e89cb6357f0019c246b19aa594))

## v1.20.2 (2021-01-01)
### Fix
* Remove authority header ([`03c11ce`](https://gitlab.com/keatontaylor/alexapy/-/commit/03c11ce09df6559af8cefa657a74d6d7aa086734))

## v1.20.1 (2021-01-01)
### Fix
* Fix types to ensure strings returned ([`e897d64`](https://gitlab.com/keatontaylor/alexapy/-/commit/e897d64ca0bff2904f1c89aa840de7473a761b2e))

## v1.20.0 (2021-01-01)
### Feature
* Add check_domain command ([`0578cc1`](https://gitlab.com/keatontaylor/alexapy/-/commit/0578cc1379c071d338806aae2f37bf71573146c4))

### Fix
* Handle oauth for non .com domains ([`4d6b6f7`](https://gitlab.com/keatontaylor/alexapy/-/commit/4d6b6f74bfe856405736881ff06d548b67554438))

## v1.19.0 (2021-01-01)
### Feature
* Add get_csrf function ([`ff68689`](https://gitlab.com/keatontaylor/alexapy/-/commit/ff68689e25e148799d8b1d9e1245a519ea0a856a))

### Fix
* Add uuid to AlexaLogin ([`44709c6`](https://gitlab.com/keatontaylor/alexapy/-/commit/44709c6aa78d5b723c0d42e3570ab6caa9bd0dcb))
* Add obfuscaton on tokens ([`e55cbb3`](https://gitlab.com/keatontaylor/alexapy/-/commit/e55cbb3dd54f19b491b69ddf0435724fa814a0a7))

## v1.18.0 (2020-12-31)
### Feature
* Add oauth token refresh ([`7bf192e`](https://gitlab.com/keatontaylor/alexapy/-/commit/7bf192eb497834323efb49f9a6b5b7a3217b8691))

### Fix
* Save cookie with user provided domain ([`6f380a3`](https://gitlab.com/keatontaylor/alexapy/-/commit/6f380a323c60ee3937af146fdb43e5127b250eb2))
* Fix handling of auto 2fa submission ([`3ee08dc`](https://gitlab.com/keatontaylor/alexapy/-/commit/3ee08dc2be35baeca0f52bbcd9ee5d7416e474fc))
* Add timestamp to get requests ([`0483ced`](https://gitlab.com/keatontaylor/alexapy/-/commit/0483ced938680d24b15ff0311027afa148782e76))

## v1.17.2 (2020-12-12)
### Fix
* Prevent api connections when login invalid ([`65a6b58`](https://gitlab.com/keatontaylor/alexapy/-/commit/65a6b58ac7c31c101b3c6b2a91d3f45ebc68b610))
* Suppress unnecessary token errors ([`4f64940`](https://gitlab.com/keatontaylor/alexapy/-/commit/4f6494007d27efe92979a9e0cba6edb12a9147b9))

## v1.17.1 (2020-12-11)
### Fix
* Add routine search on name field ([`650f19b`](https://gitlab.com/keatontaylor/alexapy/-/commit/650f19bfba6a215c49da4e590fb22638643232d2))
* Add error checking for 2fa key token ([`60131f4`](https://gitlab.com/keatontaylor/alexapy/-/commit/60131f465370067eef6c44403f40db5c18cd5168))
* Properly handle obfuscation of short serials ([`de641be`](https://gitlab.com/keatontaylor/alexapy/-/commit/de641bea20575eea07a04f3aeeeed27a42bfcf47))

## v1.17.0 (2020-12-05)
### Feature
* Add custom command ([`fd56f3b`](https://gitlab.com/keatontaylor/alexapy/-/commit/fd56f3b8011ae3353d2a62f1d0443b85216585df))

## v1.16.0 (2020-11-27)
### Feature
* Add stats collection ([`dd4a8cb`](https://gitlab.com/keatontaylor/alexapy/-/commit/dd4a8cbc186af00caab1da214c7dcbcf8a8ee51c))
* Add time-based otp generator ([`3755715`](https://gitlab.com/keatontaylor/alexapy/-/commit/3755715fc3dedcf55d9b615a17c8492437181643))
* Expose save_cookiefile function ([`2646f58`](https://gitlab.com/keatontaylor/alexapy/-/commit/2646f58d6ce68799e8e55af10bce8564f8655229))

### Fix
* Append otp to password without input data ([`7ac52d1`](https://gitlab.com/keatontaylor/alexapy/-/commit/7ac52d12dd55ab4c5068e8c97f02317a20196752))
* Remove redundant cookie save ([`f831713`](https://gitlab.com/keatontaylor/alexapy/-/commit/f83171397dc25813f32a23dd821f7119682afa7b))
