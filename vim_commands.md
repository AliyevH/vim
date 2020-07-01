# vim commands

# Go to the beginning of the text.  
gg

# Go to the end of the text   
G - (shift + g)

# Delete all lines from any file   
:1,$d

# Select all lines from any file   
ggVG

# Select all lines from current line till end of file   
VG

# Select all lines from current line till start of file   
Vgg

# Select all lines from current cursor position till end of file   
vG

# Select all lines from current cursor position till start of file   
vgg


# Find each occurrence of 'foo' (in all lines), and replace it with 'bar'   
:%s/foo/bar/g

# Find each occurrence of 'foo' (in the current line only), and replace it with 'bar'   
:s/foo/bar/g

# Change each 'foo' to 'bar' for all lines from line 5 to line 12   
:5,12s/foo/bar/g	

