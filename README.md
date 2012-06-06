bbips
=====

Bash batch image processing scripts
-
A collection of bash scripts that use Imagemagick to "batch" process entire directories of images all at once. For use with Linux and Unix systems to batch process *.jpg image files from the bash shell.

######################################################
#    Revised 06/05/2012  -- Dave Crouse
#
#    README.txt  --- yeah, you should :P
#
# REQUIREMENTS: Imagemagick
#
# This is what I do with these scripts, feel free
# to do this however you want though.
#
# 1. Create a .bbips directory in your /home
# 2. Move all of these files into your .bbips
#    directory. 
# 3. Make sure they have executable permissions.
#        chmod a+x bb*
# 4. Copy and paste the following alias's 
#    into your .bashrc file.
# 5. Remember the command bbhelp ;)
# 6. Have fun !
#
#
#  NOTE: These commands run as a normal user this
#        way and don't require anything special 
#        to install as a normal user.         
#
#        BE AWARE - These commands WILL alter your
#        current images !!!!! ALWAYS work on 
#        copies and NOT originals unless you
#        REALLY know what your doing !!!!
#        This is WHY we included the bbcopy 
#        script !!!
#                      You have been WARNED :)
#
#
######################################################


# Add the following lines to your .bashrc file



alias bbapcom='bash ~/.bbips/bbapcom'
alias bbatxt='bash ~/.bbips/bbatxt'
alias bbborder='bash ~/.bbips/bbborder'
alias bbcolorize='bash ~/.bbips/bbcolorize'
alias bbcopy='bash ~/.bbips/bbcopy'
alias bbhelp='bash ~/.bbips/bbhelp'
alias bbindex='bash ~/.bbips/bbindex'
alias bbnormalize='bash ~/.bbips/bbnormalize'
alias bbpaint='bash ~/.bbips/bbpaint'
alias bbflip='bash ~/.bbips/bbflip'
alias bbflop='bash ~/.bbips/bbflop'
alias bbgamma='bash ~/.bbips/bbgamma'
alias bbgrayscale='bash ~/.bbips/bbgrayscale'
alias bbgzip='bash ~/.bbips/bbgzip'
alias bbrecom='bash ~/.bbips/bbrecom'
alias bbresize='bash ~/.bbips/bbresize'
alias bbrotate='bash ~/.bbips/bbrotate'
alias bbsepia='bash ~/.bbips/bbsepia'
alias bbsolarize='bash ~/.bbips/bbsolarize'
alias bbwrcom='bash ~/.bbips/bbwrcom'
alias bbrename='bash ~/.bbips/bbrename'
alias bbshot='bash ~/.bbips/bbshot'
alias bbgallery='bash ~/.bbips/bbgallery'
alias bbgallery2='bash ~/.bbips/gallery2'
