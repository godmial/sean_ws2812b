from building import *
import rtconfig

cwd = GetCurrentDir()

src = Glob('*.c')
CPPPATH = [cwd]
LOCAL_CCFLAGS = ''

if GetDepend(['SEAN_WS2812B_USING_DEMO']):
    src += Glob('examples/*.c')

group = DefineGroup('sean_ws2812b', src, depend = ['PKG_USING_SEAN_WS2812B'], CPPPATH = CPPPATH, LOCAL_CCFLAGS = LOCAL_CCFLAGS)

Return('group')
