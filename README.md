1. 先下載relone:
 ```
sudo apt install rclone
#測試是否下載成功

rclone
```
2. 將編輯rclone.conf，並將其放到~/.config/rclone/rclone.conf的路徑中

測試指令(會顯示pure storage的檔案):
```
rclone ls tc_test:cloud-backup-poc/trusted_backup_test/
```
