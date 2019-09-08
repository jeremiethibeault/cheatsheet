# Keytool

## Commands

### genkey

- `keytool -genkey -v -keystore myapp-release.keystore -alias {alias} -keyalg RSA -keysize 2048 -validity 10000` : Generates a keystore.

**Parameters in order**:
- Alias (alias)
- Keystore password (storepass)
- Key password (keypass)

### list
- `keytool -list -v -keystore myapp-release.keystore -alias {alias} -storepass {storepass} -keypass {keypass}` : Gets the keystore metadata (e.g. SHA1, SHA256).

- `keytool -list -v -keystore ~/.android/debug.keystore -alias androiddebugkey -storepass android -keypass android` : Gets the debug keystore metadata (e.g. SHA1, SHA256).