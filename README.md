# 18408-2
find_max_and_min

#!/usr/bin/env python
# -*- coding:utf-8  -*-

def find_max_and_min(L):
    if len(L)==0:
        return (None,None)
    else:
        max=L(0)
        min=L(0)
        for i in L:
            if i>max:
                max=i
            if i<min:
                min=i
        return(max,min)
