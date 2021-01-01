# Changelog

<!--next-version-placeholder-->

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
