# ETHPM package own3d
Brings onlyowner modifier, transferOwnership function and kill function to your project.

Add to your project via
```sh
truffle install own3d
```
[Truffle ETHPM Docs](https://truffleframework.com/docs/truffle/reference/configuration)



Import to your contract via
 ```js
import "own3d/owned.sol";

contract YourContract is owned {
}
```

Inspired by [example-package-owned](https://github.com/ethpm/example-package-owned)

