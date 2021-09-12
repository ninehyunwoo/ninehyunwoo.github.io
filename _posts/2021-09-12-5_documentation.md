print ('메뉴얼과 검색')

import urllib.request
with urllib.request.urlopen('http://python.org/') as response:
   html = response.read()

print ('tutorial')
print ('library reference')
print ('language reference')