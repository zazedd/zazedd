
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

let working_on = ("zaml", "A type-inferred, statically typed functional programming language inspired by OCaml and Lambda calculus.")
```

---
<a href="https://github.com/anuraghazra/convoychat">
  <img height=200 align="center" src="https://github-readme-stats-two-nu-79.vercel.app/api?username=zazedd&show_icons=true&hide_border=true&theme=dark&bg_color=00000000&card_width=400" />
</a>
<a href="https://github.com/anuraghazra/github-readme-stats">
  <img height=200 align="center" src="https://github-readme-stats-two-nu-79.vercel.app/api/top-langs/?username=zazedd&layout=compact&theme=dark&include_all_commits=true&hide_border=true&count_private=true&langs_count=6&hide=html,lua,css,tex&bg_color=00000000&card_width=300" />
</a>

