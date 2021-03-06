# quick-vim

                              {__                                      
                     {_       {__                       {_             
      {__   {__  {__      {___{__  {__      {__     {__   {___ {__ {__ 
    {_  {__ {__  {__{__ {__   {__ {__ {_____ {__   {__ {__ {__  {_  {__
    {_  {__ {__  {__{__{__    {_{__           {__ {__  {__ {__  {_  {__
     {__{__ {__  {__{__ {__   {__ {__          {_{__   {__ {__  {_  {__
        {__   {__{__{__   {___{__  {__          {__    {__{___  {_  {__
        {___                   
                                                                       
Portable text exiting for devs.

## the problem

When software does many things it sacrifices doing one thing very well. Instead of trying to make vim a clumsy "does it all" IDE `quick-vim` is lightweight, relies on simple defaults, thusly very portable and easily repeatable text editor. 

## solution

- three use cases: install, upgrade, and uninstall

## the bundles for me

This is a portable text editor for doing dev on the run, in a shell, probably on a temporary machine, possibly drunk. Vim is surprisingly powerful stand-alone, odds are you don't *really* need a particular plugin bundle. Try to work with the stock install. You'll be surprised! And less, dependant on custom schemes. (Ironic words for a vim config project, I know.)

If you do need more, you can always fork this repo, create a branch, modify the bundles.txt to your hearts desire. If you find a bundle that meets the criteria above that you think I should check out: pls send a pull request!

## usage

Getting started with `quick-vim` is easy:

    git clone git://github.com/brianleroux/quick-vim.git
    cd quick-vim
    ./quick-vim install

You can reset to the default/previous vim env simply:

    ./quick-vim uninstall

Brute force upgrade everything:

    ./quick-vim upgrade

And thats it.

