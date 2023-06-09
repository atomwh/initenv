## This is my linux config for bash, vim and history search                        
***                                                                                
                                                                                   
### 1. bashrc config                                                               
1. make **grep** colorful                                                          
2. make **ls** more comfortable                                                    
3. make **tree** more comfortable                                                  
4. use vim replace vi                                                              
5. add shortcut for `history`                                                      
6. alias **fullpath** to `readlink -f`                                             
7. enable fzf key-bindings                                                         
8. add shortcuts for directory moving                                              
9. set history format                                                              
10. use vim as default editor                                                      
11. use hg to quickly find history                                                 
12. enable scientifical network                

***
                                                                                   
### 2. vimrc                                                                       
used plugins:                                                                      
* nerdtree                                                                         
* nerdcommentor                                                                    
* ALE                                                                              
* vim-color-solarized                                                              
* vim-airline                                                                      
* vim-airline-themes                                                               
* fzf                                                                              
* leaderf                                                                          
                                                                                   
I use leaderf to quickly find functions and definations in source code which fzf
must use ctags to generate tags file previously.                       

***
                                                                                   
### 3. inputrc                                                                     
enable PageUp and PageDown for history command search
