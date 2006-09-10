This is a mirror of http://www.vim.org/scripts/script.php?script_id=1649

" This plugin, scrollfix, maintains cursor at fixed visual line of window
" (except near beginning of file and near end of file. The
" latter is configurable. You can choose whether to fix cursor
" near end of file or not, see g:fixeof below). This is enhancement
" to the 'set scrolloff=999', but scrollfix allows any visual line of
" window to keep cursor at, not only middle line of window.
"
" MAIN CONTROL VARIABLE, THE g:scrollfix:
"
" You choose the visual line of screen in percentages from top of screen:
"     let g:scrollfix=100 " means lock cursor at bottom of window
"     let g:scrollfix=0   " means keep cursor at top line of window
"     let g:scrollfix=50  " means middle line of screen
"     let g:scrollfix=66  " means two-third from top of screen
" As shipped, cursor is at 60% (let g:scrollfix=60)
"
" CONTROL VARIABLES:
" To change plugin settings, assign to following variables in your .vimrc.
" g:scrollfix - percentage from top of screen where to lock cursor
"               -1 - disables. Default: 60
" g:fixeof    - 1=>fix cursor also near end-of-file; 0=>no. Default:0
" g:scrollinfo - 1=>inform when scrollfix is turned on, 0=>no. Default: 1
" :FIX NNN         comand :FIX is alternate way to change g:scrollfix variable
"
" NB:
" - You need vim version at least 7.0.91 or later (vim6 won't work).
"   If you have vim7 before 7.0.91, you can use script#1473 to build
"   & install the latest vim7 executable.
" - this is beta version of the scrollfix plugin.
"   Your feedback is welcome. Please send your feedback to iler at gmail dot com.
"................................................................

