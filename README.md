# ska
SSH增强命令，可以使用-a选项将本机的公钥直接添加到远程机器，下次ssh登录即可免密码

#用法
将本脚本复制或者软链接到PATH目录（/usr/bin，/usr/local/bin...）下
alias ssh = 'ska -h'
可以使用ska命令代替无选项的ssh命令

ska -h [USER@]HOST [-a][-p LOCAL_PUBLICKEY_FILE]
