# Example to execution run_clone_d3_caravel_user_project

1. download [run_clone_d3_caravel_user_project](https://github.com/TonyHo722/caravel_user_project/blob/30d93b48937cb47114d2d4a561b023514011502b/bash_auto/run_clone_d3_caravel_user_project) to ~/run_clone_d3_caravel_user_project

2. chmod +x ~/run_clone_d3_caravel_user_project

3. update [run_clone_d3_caravel_user_project](https://github.com/TonyHo722/caravel_user_project/blob/30d93b48937cb47114d2d4a561b023514011502b/bash_auto/run_clone_d3_caravel_user_project#L6)
```
export MF=/home/tonyho/workspace/debug/d3_caravel_user_project
```
- change to your path

4. execution d3_caravel_user_project
```
$ ~/d3_caravel_user_project 2>&1 | tee run_clone_d3.log
```

