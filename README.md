zech32
==========

Package zech32 provides a Go implementation of the bech32 format used by Zcash.  It's identical to the one specified in [BIP 173](https://github.com/bitcoin/bips/blob/master/bip-0173.mediawiki) except that the permissible length of a string is much longer. The canonical reference for the Zcash format can be found at [ZIP 173](https://zips.z.cash/zip-0173).

## Examples

The same examples from btcsuite's docs still apply.

* [Bech32 decode Example](http://godoc.org/github.com/btcsuite/btcutil/bech32#example-Bech32Decode)
  Demonstrates how to decode a bech32 encoded string.
* [Bech32 encode Example](http://godoc.org/github.com/btcsuite/btcutil/bech32#example-BechEncode)
  Demonstrates how to encode data into a bech32 string.

## License

Package zech32 is licensed under the [copyfree](http://copyfree.org) ISC License.
