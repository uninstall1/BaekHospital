# 프레드보트
디스코드 음성 채널에서 음악을 듣고 싶은 사람들을 위해서 프레드보트(FredBoat)가 도입되었다. 여기에서는 간략한 사용법만을 다룰 예정이므로, 자세한 기능과 명령어에 대해서는 [이 링크](https://fredboat.com/docs#music-commands)에 들어가 직접 확인하길 바란다.  

## 재생할 수 있는 것들
보통은 YouTube 링크만을 사용하지만, 프레드보트는 다양한 곳에서 음악을 가져와 재생할 수 있다.

* 유튜브(YouTube)
* 사운드클라우드(SoundCloud)
* 밴드캠프(BandCamp)
* 트위치(Twitch)
* 비메오(Vimeo)
* 믹서(Mixer)
* [Wastebin](https://wastebin.party/)에 업로드 된 음악 링크 목록

이외에도 스포티파이(Spotify) 재생목록을 가져와 재생할 수 있지만 이는 Patron 기부자 전용 기능이므로 설명하지 않는다.  
주의할 점은 미국에서 접근이 제한된 YouTube 영상을 재생할 수 없다. 서버가 미국에 있어서 그런듯 하다.

## 명령어 목록
### ;;play [;;p]
``;;play [URL]`` 혹은 ``;;play [YouTube/SoundCloud 검색 단어]``같은 방식으로 사용한다. 음악 재생 큐에 해당 영상/음악을 넣는다.
### ;;queue [;;q]
현재 큐에 들어있는 노래 목록을 확인한다.
### ;;nowplaying [;;np]
현재 재생중인 노래를 확인한다.
### ;;skip [;;s]
현재 재생중인 노래를 건너뛴다.
### ;;stop [;;st]
재생을 멈추고 큐에 있는 모든 노래를 제거한다. **디스코드 관리자 전용 명령어**.
### ;;pause
노래 재생을 일시중지 한다.
### ;;resume
일시중지한 노래를 다시 재생한다.
### ;;join [;;j]
해당 명령어를 입력한 사람이 참가한 음성 채널에 프레드보트가 들어가 음악을 재생하도록 한다.
### ;;leave [;;lv]
프레드봇이 현재 참가한 음성 채널에서 나가도록 한다.