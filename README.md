# Global vim settings

Sets color scheme (grovebox), tab support, syntax highlight, quick file opener, autocomplete and others. Installs required plugins automatically. Tested on Debian & Ubuntu.

## Reuirements

- curl
- vim

## Global installation

Running `sudo vim` for the first time installs necessary plugins. You will get couple error messages until plugins get installed (just make sure `curl` command is available).

   ```
   { ~ } » git clone https://github.com/petrzpav/vimrc.git
   { ~ } » sudo mkdir /etc/vim/autoload
   { ~ } » sudo chmod 777 /etc/vim/autoload
   { ~ } » sudo ln -sf ~/vimrc/vimrc* /etc/vim
   { ~ } » mkdir .vim
   { ~ } » sudo vim
   ```

