1. Add toolchain directory variable to User Environment Variables:
ST_TOOLCHAIN_DIR    C:\...\ST_Toolchain

2. Add following variables to the User Environment Variables PATH:
%ST_TOOLCHAIN_DIR%\GnuWin32\bin
%ST_TOOLCHAIN_DIR%\arm-gcc\10_2020-q4-major\bin
%ST_TOOLCHAIN_DIR%\stlink-1.7.0-x86_64-w64-mingw32\bin
%ST_TOOLCHAIN_DIR%\openocd-v0.11.0-i686-w64-mingw32\bin
%ST_TOOLCHAIN_DIR%\netcat-win32-1.12

3. UART host monitor cmd: plink -serial COM3 -sercfg 115200,8,n,1,N
