# 2014-10-17 VimMacro��Y��Ȃ�

Vim��Macro������I�Ɍ��ʓI��������ʂɑ��������̂ŁA����͂����Ǝg���Ă����Ȃ���΂Ȃ�Ȃ��Ǝv��������B
�悭�R�}���h��Y���̂ŁA�����Ċo���Ĕ��Y�Ƃ���B


## ������{�I�ȃ}�N���̎菇

* �}�N���L�^�J�n

``` VimCommand
qa
```
q�Ń}�N���N���Aa�͔C�ӂ̕����L�[�ŁA�}�N�����L�^���郌�W�X�^�ƂȂ�B


* �}�N���L�^

�X�e�[�^�X������"�}�N���L�^��"�Əo��̂ŁA��������肫�낭�B


* �}�N���L�^�I��

``` VimCommand
q

```
* �}�N���N��

``` VimCommand
@a

```
a�̓��W�X�^�̕����L�[�B


## ���񑘋��������ʓI���

1. SQL��INSERT��100���R�[�h�����B
2. �C���f�b�N�X��(��Ӑ���̂���A�Ԃɂ��ׂ�����)��L����
3. ���̗��NULL�܂��͗񂲂Ɠ����l�ŗǂ�

�Ƃ����悤�ȏ����B

* �s�����N&�y�[�X�g
* �C���f�b�N�X�l�̃C���N�������g

�����ŊȒP��1�񕪂͋L�^�ł���B

�R����������T�N���G�f�B�^�Ȃ񂩂ł��o�������Ȃ��̂���(��2)�A
Vim�̓����Ƃ��āA�قڂ��ׂẴR�}���h�ɂ͈����Ƃ��ČJ��Ԃ�����ݒ�ł���B

���̂��߁c

``` VimCommand
50@a
```

��50�񕪉񂵂�50���R�[�h��INSERT�������������B(��2)

![increment_macro_result](./Images/increment_macro_result.jpg)


���I��I�ցI���I

---

��1 �T�N���G�f�B�^�ɂ̓C���N�������g�̋@�\���Ȃ������BVim�̈�l�������I
��2 �s�����N�y�[�X�g�ŃJ�[�\�������[�Ɋ�邱�Ƃ�A�J�[�\����w�L�[��n�P�ꕪ�̈ړ��Ƃ���Ȃǃ}�N�����̎����ω��ɂ��܂��Ǐ]����M�~�b�N�������Ă���B