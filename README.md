# GitHub Action: Install Savi

A GitHub Action to install Savi in the current job runner.

## Example

```yaml
jobs:
  test:
    runs-on: ubuntu-latest
    steps:
      - uses: savi-lang/action-install@v1.0.0
      - run: savi eval 'env.out.print("Savi is installed!")'
```
