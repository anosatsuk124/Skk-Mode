�͂��߂�
========

����́u�����Ō����I�ȓ��{����͊���񋟂���V�X�e��SKK�v��xyzzy�ڐA��
�ł��BGNU General Public License �ɏ]�����t���[�E�\�t�g�E�F�A�Ƃ��Ĕz�z
����܂��B

�ڐA��Ƃɂ����ăx�[�X�ɂ����̂�SKK8.6�ŁA���̃V�X�e���̂���skk.el�t�@�C
���̃R�A�ȕ����������ڐA���Ă���܂��B


�C���X�g�[��
============

�����̓���
----------

���̃p�b�P�[�W�ɂ͕ϊ��������܂܂�Ă��܂���̂ŁA�܂���������肵�Ă���
�����B���̃T�C�g����_�E�����[�h�ł��܂��B

    http://openlab.ring.gr.jp/skk/wiki/wiki.cgi?page=SKK%BC%AD%BD%F1

���肵�������͂��D���ȃt�H���_�ɃR�s�[���Ă����Ă��������B

�t�@�C���̔z�u
--------------

�z�z���Ă���A�[�J�C�u�t�@�C���͂����������̂悤�ȍ\���ɂȂ��Ă��܂��B

    + site-lisp
      + skk
        + readme.txt     - ���̕���
        + autoloads.l
        + skk.l          - skk�{��
        + skk.lc
        + skk-gadget.l   - �ϊ����s�p�̃��W���[��
        + skk-gadget.lc
        + skk-sticky.l   - skk���l������sticky-shift
        + skk-sticky.lc
        + COPYING.txt
      + ni-autoload
        +  kiaswebsite
           + skk.l

�A�[�J�C�u�t�@�C����W�J���Asite-lisp�t�H���_�̉��ɂ���skk�t�H���_�Ƃ���
���̃t�@�C����xyzzy��site-lisp�t�H���_�ɃR�s�[���Ă��������B

ni-autoload�t�H���_�́ANetInstaller�̎����ǂݍ��݋@�\�Ɋ֌W����t�@�C����
�����Ă��܂��B���̋@�\���g��Ȃ��ꍇ�͂��̃t�H���_�ƒ��̃t�@�C���͕s�v�ł��B


�͂��߂̐ݒ�
============

__���L�̂悤�Ȑݒ���I������xyzzy���ċN�����Ă��������B__

__�Ȃ����݂̔łł�user�p�b�P�[�W�ł͂Ȃ�skk�p�b�P�[�W���g���悤�ɂȂ���
���܂��B__�ȑO�̔ł���A�b�v�O���[�h�����ꍇ�̓J�����g�p�b�P�[�W�̏�Ԃ�
���ӂ��Đݒ���C�����Ă��������B~/.skk�t�@�C���͐擪��(in-package "skk")
�Ə��������Ƒ����̏ꍇOK�ł��傤�B


��{�ݒ�
--------

���̂悤�� ~/.xyzzy �t�@�C���ɋL�q���܂��B

    (require "skk/autoloads")
    (setq skk:*skk-large-jisyo* "C:/path/to/SKK-JISYO.L")
    (global-set-key '(#\C-x #\C-j) 'skk:skk-mode)
    (global-set-key '(#\C-x #\j) 'skk:skk-auto-fill-mode)

������skk:*skk-large-jisyo*�ɂ͕ϊ������ւ̃p�X��ݒ肵�܂��B��Ƀ_�E�����[
�h���Ă����������t�@�C�����R�s�[�����t�H���_��K�؂Ɏw�肵�Ă��������B

NetInstaller��ni-autoload���g���ꍇ��(require "skk/autoloads")�̕����͕s
�v�ł��B(ni-autoload)�̌�ɐݒ���L�q����悤�ɂ��Ă��������B

�����T�[�o�̐ݒ�
----------------

�����T�[�o���g�������Ƃ���skk:*skk-server-host*�ɃT�[�o�������Ă���z�X
�g����������IP�A�h���X���w�肵�܂��B���̂悤�Ȑݒ��ǉ����Ă��������B
�A�N�Z�X��̃|�[�g�ԍ���skk:*skk-portnum*�Ŏw��ł��܂��B

    (setq skk:*skk-server-host* "192.168.0.88")
    (setq skk:*skk-portnum* "2178")

����SKK�V�X�e���ƌl�����ɂ���
---------------------------------

SKK���g���܂��Ƃ��̗��p�ɉ����Čl������ǂݏ������邱�ƂɂȂ�܂��B

�l�����͖�����Ύ����ō쐬����܂����A�f�t�H���g�̏�Ԃł�~/.skk-jisyo
�Ƃ����t�@�C���ł��B�܂����̍Ō�̍X�V�̒��O�̓��e��~/.skk-jisyo.BAK�Ƃ�
���t�@�C���Ƀo�b�N�A�b�v�����悤�ɂȂ��Ă��܂��B

�����A���Ƃ���Meadow�Ȃǂ�SKK�𗘗p���Ă��āA�����l�����𓯎��Ɏg����
���܂����悤�Ȏ��ɂ͎��������Ă��܂����Ƃ��l�����܂��B���̂悤�ȏꍇ
�ɂ͐���Ƃ��l�����𕪂��Đݒ肷��悤�ɂ��Ă��������B

�l�����t�@�C���Ƃ��̃o�b�N�A�b�v�t�@�C���� skk:*skk-jisyo*�A
skk:*skk-backup-jisyo*�Ƃ����ϐ��ł��ꂼ��w��ł��܂��B�Ȃ��A
skk:*skk-jisyo-code*�Ŏ����ۑ����̕����R�[�h���w�肷�邱�Ƃ��ł��܂��B

    (setq skk:*skk-jisyo* "~/.skk-jisyo-xyzzy")
    (setq skk:*skk-backup-jisyo* "~/.skk-jisyo-xyzzy.BAK")
    (setq skk:*jisyo-code* *encoding-euc-jp*)


��{�I�Ȏg����
==============

SKK���N������ɂ�C-x C-j�A��������C-x j�ƃ^�C�v���܂��B

SKK���I������ɂ�C-x C-j�A��������C-x j�ƃ^�C�v���܂��B

���ۂ̕ϊ�����ɂ��Ă�Emacs�ł�SKK�̑���ɏ����܂��̂ŁA�����̐�����
�Q�Ƃ��Ă��������B���̃A�h���X����SKK���[�U�}�j���A���Ȃǂ����邱�Ƃ���
���܂��B

    http://openlab.jp/skk/index-j.html


Rev.139����Rev.236�ւ̕ύX�_
============================

�ȉ��͂�����SANO Masatoshi����̍�Ƃɂ����̂ł��B���肪�Ƃ��������܂�m(_ _)m

*   (defpackage "skk")�����Ă��̒��ɓ����悤�ɂ����B
*   annotation�t���̎����֑Ή������B
*   �����ɓ����Ă���elisp�̃R�[�h��ϊ����s�ł���悤�ɂ����B


;; End.
