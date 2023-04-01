
studying at ubi, portugal

```
let github = [ "!"; "profile"; "GitHub"; "my"; "to"; "Welcome" ]

let () =
  List.fold_left
    (fun acc a ->
      match a with "!" | "Welcome" -> a ^ acc | _ -> " " ^ a ^ acc)
    "" github
  |> print_endline
```

---
![](https://github-readme-stats.vercel.app/api?username=zazedd&theme=dark&hide_border=true&include_all_commits=true&count_private=false)<br/>
---
![](https://github-readme-stats.vercel.app/api/top-langs/?username=zazedd&theme=dark&hide_border=true&include_all_commits=true&count_private=false&layout=compact)
