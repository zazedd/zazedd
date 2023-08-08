
studying at ubi, portugal

```ocaml
let lst = [ "Welcome"; "to"; "my"; "GitHub"; "profile"; "!" ]

let () =
  List.fold_left
    (fun acc a ->
      match a with "!" | "Welcome" -> acc ^ a | _ -> " " ^ acc ^ a)
    "" lst
  |> print_endline

let interests = [|
  "Functional Programming";
  "Compilers and Interpreters";
  "Type Theory";
  "Cybersecurity";
|]

let working_on = ("zaml", "A type inferred, statically-typed functional programming language inspired by OCaml")
```

---
![](https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=zazedd&theme=dark&hide_border=true&include_all_commits=true&count_private=false&layout=compact&hide=lua,css,html)
