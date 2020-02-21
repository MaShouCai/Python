### 第二次尝试

import time

start\_time = time.time\(\)

\# 注意是两重循环

for a in range\(0, 1001\):

    for b in range\(0, 1001-a\):

        c = 1000 - a - b

        if a\*\*2 + b\*\*2 == c\*\*2:

            print\("a, b, c: %d, %d, %d" % \(a, b, c\)\)

end\_time = time.time\(\)

print\("elapsed: %f" % \(end\_time - start\_time\)\)

print\("complete!"\)

运行结果：

a, b, c: 0, 500, 500

a, b, c: 200, 375, 425

a, b, c: 375, 200, 425

a, b, c: 500, 0, 500

elapsed: 0.182897

complete!

注意运行的时间:0.182897秒第二次尝试

import time

start\_time = time.time\(\)

\# 注意是两重循环

for a in range\(0, 1001\):

    for b in range\(0, 1001-a\):

        c = 1000 - a - b

        if a\*\*2 + b\*\*2 == c\*\*2:

            print\("a, b, c: %d, %d, %d" % \(a, b, c\)\)

end\_time = time.time\(\)

print\("elapsed: %f" % \(end\_time - start\_time\)\)

print\("complete!"\)

运行结果：

a, b, c: 0, 500, 500

a, b, c: 200, 375, 425

a, b, c: 375, 200, 425

a, b, c: 500, 0, 500

elapsed: 0.182897

complete!

注意运行的时间:0.182897秒

