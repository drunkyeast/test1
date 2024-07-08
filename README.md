# test 1
# 第一次在github上面修改文件
# 失误了, 我现在把.git README.md移动到test1/目录中了, 
# 又经历很多操作, rebase, 分支, origin/testbranch1分支, 之后有删除了这分支, 全靠chatgpt和Learn Git Branching
# 我打算长期保留这项目test1, 用于git的不断实操学习.
今天是2024年6月1日, 在yxc那里学的git操作的基础上, 学完了Learn Git Branching, 然后实操. 感觉git还有很多知识要学习. 以后应该不会有时间再这么花一整天时间来系统学习了. 实习工作慢慢积累git知识吧. 最后再夸一下chatgpt, 当初没有chatgpt学习git真的好累.
# 查看完整的树状结构
git log --graph --oneline $(git rev-parse HEAD origin/main) $(git fsck --full --no-reflogs --unreachable --lost-found | grep commit | awk '{print $3}')
# 一些操作以及amend
~~ #lwh ~~
