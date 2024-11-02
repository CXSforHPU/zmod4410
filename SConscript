import os
from building import *

objs = []
cwd  = GetCurrentDir()
ls = os.listdir(cwd)

for item in ls:
    if os.path.isfile(os.path.join(cwd, item, 'SConscript')):
        objs = objs + SConscript(os.path.join(cwd,item, 'SConscript'))

Return('objs')
