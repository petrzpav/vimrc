# Global vim settings

Sets color scheme (grovebox), tab support, syntax highlight, quick file opener, autocomplete and others. Installs required plugins automatically. Tested on Debian & Ubuntu.

## Reuirements

- curl
- vim

## Global installation

Running `sudo vim` for the first time installs necessary plugins.

   ```
   { ~ } » git clone https://github.com/petrzpav/vimrc.git
   { ~ } » sudo mkdir /etc/vim/autoload && chmod 777 /etc/vim/autoload
   { ~ } » sudo ln -sf ~/vimrc/vimrc* /etc/vim
   { ~ } » mkdir .vim
   { ~ } » sudo vim
   ```

