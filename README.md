![Your GitHub Stats](https://github-readme-stats.vercel.app/api?username=yourusername&show_icons=true&theme=dark)

![Visitor Count](https://komarev.com/ghpvc/?username=yourusername&color=blue)

![GitHub Badge](https://img.shields.io/github/followers/yourusername?label=Followers&style=social)

[![GitHub Profile Card](https://github-readme-stats.vercel.app/api/pin/?username=yourusername&repo=yourrepo&theme=dark)](https://github.com/yourusername/yourrepo)

import time

def countdown_timer(seconds):
    while seconds:
        mins, secs = divmod(seconds, 60)
        timeformat = '{:02d}:{:02d}'.format(mins, secs)
        print(timeformat, end='\r')
        time.sleep(1)
        seconds -= 1
    print("Time's up!")

countdown_timer(60)  # Timer 1 menit
