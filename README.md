# -perl-
perl语言文字处理

#打开文件目录
#1）给出语料eagle.zip 编写程序，完成：
#a）列出每个文件的文件名和大小，并统计整个语料的大小
#b) 统计每个文件的字频和总字频，分别输出到文件中。



opendir (Dir,"eagle");
@File=readdir(Dir);
foreach $file_name(@File)
{
    print "$file_name\n";
}
close(Dir);
