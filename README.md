
studying at fcup, portugal  

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

let working_at = ("ahrefs", "improving internal tools")
```

also check out my [website](https://leoms.dev)

---
<a>
  <img height=200 align="center" src="https://github-readme-stats-two-nu-79.vercel.app/api?username=zazedd&show_icons=true&hide_border=true&theme=dark&bg_color=00000000&card_width=400" />
</a>
<a>
  <img height=200 align="center" src="https://github-readme-stats-two-nu-79.vercel.app/api/top-langs/?username=zazedd&layout=compact&theme=dark&include_all_commits=true&hide_border=true&count_private=true&langs_count=6&hide=html,css,tex&bg_color=00000000&card_width=300&exclude_repo=solar-system,money" />
</a>
