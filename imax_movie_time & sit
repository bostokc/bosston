import requests
from bs4 import BeautifulSoup

url = '''http://www.cgv.co.kr//common/showtimes/iframeTheater.aspx?areacode=01&theatercode=0199&date=20190803
        &screencodes=&screenratingcode=&regioncode='''  # f12 안에 있는 사이트 요소를 배서 cgv 홈페이지 주소뒤에 붙인것
html = requests.get(url)
soup = BeautifulSoup(html.text, 'html.parser')
print(soup.select_one('span.imax'))
imax = soup.select_one('span.imax')
if(imax):
    imax = imax.find_parent('div', class_='col-times')
    title = imax.select_one('div.info-movie > a > strong').text.strip()
    age = str(imax.select_one('div.info-movie > span'))
    timezone = str(imax.select_one('div.type-hall > info-timetable > a > em'))
    sit = str(imax.select_one('div.type-hall > info-timetable > a > span'))
    #print(imax.select_one('div.info-movie > a > strong').text.strip())
    #print('IMAX is available')
    print(title + ' IMAX is available')
    print(timezone)
    print(age)
else:
    print('IMAX is unavailable')




#알리미에 필요한것 영화 오픈 여부 , 열렸을때 어떤 영화가 열렸는지 제목을 알려주는 것



