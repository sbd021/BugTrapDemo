#BugTrap Demo

[BugTrap](https://github.com/bchavez/BugTrap)

3行代码：

       	BT_SetAppName(L"BugTrapDemo");
		BT_SetFlags(BTF_DETAILEDMODE | BTF_ATTACHREPORT);
		BT_InstallSehFilter();

crash的时候会弹出对话框选择dmp保存的路径。


