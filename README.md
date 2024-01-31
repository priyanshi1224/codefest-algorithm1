# codefest-algorithm1
def webSort(web):
    web.sort()

    for i in range(len(web)-1):
        if web[i][0] == web[i+1][0]:
            if web[i][1] > web[i+1][1]:
                pass
            if web[i][1] < web[i+1][1]:
                temp = web[i][1]
                web[i][1] = web[i+1][1]
                web[i+1][1] = temp
    return web
<!-- hello -->