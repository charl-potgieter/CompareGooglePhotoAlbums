Steps to compare Google photo albums with photos on  local drive
-----------------------------------------------------------------

 - Recquires at least Rclone 1.49

 - Get photos in all Google Albums with rclone and write to text file for example:
    rclone ls GooglePhotosCharl:album > GooglePhotoAlbums.201901109.txt    (or ./rclone.exe... if running from windows)
 
 - Get recursive list of folders on local drives.  On Linux this can be done with :
    du -a /tmp/dir1/
    
 - Perform a simple compare in Excel 
 
 