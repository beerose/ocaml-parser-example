# ocaml-parser-example

## Building the project

``` 
  ocamlbuild -use-menhir -tag thread -use-ocamlfind -quiet -pkg core main.native 
```

## Testing

```
  ./main.native test.json
```


