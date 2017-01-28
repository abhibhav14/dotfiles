# dotfiles
Repository to store my dotfiles

<ul>
  <li>
    <b>Vim</b>
    <ol>
      <li>
        Create a symlink to the vimrc from your home folder, like the following:
        <pre>$ln -s ./dotfiles/vim/vimrc ~/.vimrc</pre>
      </li>
      <li>
        Set up Vundle:
        <pre>$ git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim</pre>
      </li>
      <li>Launch vim and run <pre>:PluginInstall</pre></li>
    </ol>
  </li>
  <li>
    <b>i3</b>
    <ol>
      <li>
        Create a symlink to the i3 config and i3 blocks config as shown for Vim
      </li>
      <li>
        Create symlinks from the blocks scripts, or copy the contents to your i3 config golder
      </li>
    </ol>
</ul>
