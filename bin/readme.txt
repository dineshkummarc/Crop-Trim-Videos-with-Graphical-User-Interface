
            ______ ______                                  
           / ____// ____/____ ___   ____   ___   ____ _
          / /_   / /_   / __ `__ \ / __ \ / _ \ / __ `/
         / __/  / __/  / / / / / // /_/ //  __// /_/ /
        /_/    /_/    /_/ /_/ /_// .___/ \___/ \__, /
                                /_/           /____/


                build: ffmpeg-git-20181218-amd64-static.tar.xz
              version: ga1f0dd24f6

                  gcc: 6.3.0
                 yasm: 1.3.0.36.ge2569
                 nasm: 2.14

               libaom: 1.0.0-1057-g21eb040f9
               libass: 0.14.0
               libvpx: 1.7.0-1525-g368200a80
              libvmaf: 1.3.9
              libx264: 0.157.2935 545de2f
              libx265: 2.9+8-27d8424c799d
              libxvid: 1.3.4-1+b2
              libwebp: 0.5.2 
              libzimg: 2.8.0
              libzvbi: 0.2.36
             libdav1d: 0.1.1
            libgnutls: 3.5.19
            libtheora: 1.2.0alpha1+git
            libfrei0r: 1.5.0-1
           libvidstab: 1.10
          libfreetype: 2.6.3-3.2
          libharfbuzz: 2.2.0
          libopenjpeg: 2.3.0 

              libalsa: 1.1.7
              libsoxr: 0.1.3
              libopus: 1.3
             libspeex: 1.2
            libvorbis: 1.3.6
           libmp3lame: 3.100 
        librubberband: 1.8.1 
       libvo-amrwbenc: 0.1.3-1
    libopencore-amrnb: 0.1.3-2.1+b2
    libopencore-amrwb: 0.1.3-2.1+b2


      Notes: ffmpeg-10bit is no more, it's all included in ffmpeg now. 

             A limitation of statically linking glibc is the loss of DNS resolution. Installing
             nscd through your package manager will fix this.

             The vmaf filter needs external files to work- see model/000-README.TXT


      This static build is licensed under the GNU General Public License version 3.

      
      Patreon: https://www.patreon.com/johnvansickle
      Paypal:  https://www.paypal.me/johnvansickle 
      Bitcoin: 1JfPDkULqcqzAnmHQfboa3rXTLVftJJ5qt 

      email: john.vansickle@gmail.com
      irc:   relaxed @ irc://chat.freenode.net #ffmpeg
      url:   https://johnvansickle.com/ffmpeg/
