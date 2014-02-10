---
layout: post
title: "Better Deletions"
date: 2014-02-09
---
I always end up deleting words forward and backwards, an I do that by selecting stuff in Visual mode. I should stop doing that and use these.

##df
Delete forward until you find x (inclusive). If x is found, vim will delete everything from the current cursor position to and including x.

##dFx
Delete backward until you find x (inclusive). If x is found, vim will delete everything from the current cursor position to and including x.

##dtx
Delete forward until you find x (exclusive). If x is found, vim will delete everything from the current cursor position to, but not including x.

##dTx
Delete backward until you find x (exclusive). If x is found, vim will delete everything from the current cursor position to, but not including x.

Source : http://newbiedoc.sourceforge.net/text_editing/vim.html
