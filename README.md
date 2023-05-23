
studying at ubi, portugal

```
let lst = [ "Welcome"; "to"; "my"; "GitHub"; "profile"; "!" ]

let () =
  List.fold_left
    (fun acc a ->
      match a with "!" | "Welcome" -> acc ^ a | _ -> " " ^ acc ^ a)
    "" lst
  |> print_endline
```

---
![](https://github-readme-stats.vercel.app/api/top-langs/?username=zazedd&theme=dark&hide_border=true&include_all_commits=true&count_private=false&layout=compact&hide=lua)
