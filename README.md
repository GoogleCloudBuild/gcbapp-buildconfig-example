# gcbapp-go-example
The example in this repository is used in the [Cloud Build GitHub app tutorial](https://cloud.google.com/cloud-build/docs/run-builds-on-github).

#### Note: 

If you are not currently using Go modules, add the following step to the `cloudbuild.yaml` build configuration file:

```
steps:
- name: golang
  args: ['go', 'mod', 'init', 'github.com/your/import/path']
```
In this example, the specified `GOPATH` is `github.com/your/import/path`.

i love go
