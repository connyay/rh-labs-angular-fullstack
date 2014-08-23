# Red Hat Labs Angular-Fullstack

## Usage

***Heads up!***
Check the available mongodb cartridge(s) with `rhc cartridge-list` and update the create-app command accordingly. It will probably be either mongodb-2.2 or mongodb-2.4

```bash
rhc create-app <app name> "http://cartreflect-claytondev.rhcloud.com/reflect?github=connyay/openshift-node-diy" mongodb-<v>
```

```bash
cd <app name>
```

```bash
git remote add rhc git@github.com:connyay/rh-labs-angular-fullstack.git
```

```bash
git fetch rhc
```

```bash
git reset --hard rhc/master
```

```bash
git push origin -f
```
