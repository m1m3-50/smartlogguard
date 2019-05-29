### smartlogguard

`smartlogguard` is a small utility to prevent access to your machine if somebody cracked your primary password.
It is supposed to work in pair with your loginshell config.
It adds an additional password layer that has a timeout after which you will get logged out.

```
Options:

-p : Password you want to use. For passphrases please enclose with quotes.

-w : A warning you might want to show in case of failure.

-t : Set timeout - value in seconds.
```


### Example

```sh
smartlogguard -p my-passss -w "feel warned!"
```

### License

`smartlogguard` is under [MIT](https://github.com/m1m3-50/smartlogguard/blob/master/LICENSE) license.
