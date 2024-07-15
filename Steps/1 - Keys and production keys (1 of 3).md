
Resume: Deal with keys, all packages and streaming of data is compressed and encrypted, so we need to do some steps below
#### Challenges
- Get the keys from the user (A path is provide by)
- Copy the keys (prod.keys) into "keys" directory
- Load the keys into our Crypt Library
### Grab user keys
#### Before setup
- Android: Before the Main Activity, induce the user to choice the keys path
- Linux: Overlay the Main Window, induce the user to choice the keys path
> Users can avoid choice a path at startup
#### After setup (Next time ok?)

### Keys
#### Format
- (ENTRY = HASH\\n)
#### Algorithm in use
- MD5, SHA256, Android FDE
#### Regex

### API
- Classes, (KeysBank), (BlocksCypher)
- #Secret
