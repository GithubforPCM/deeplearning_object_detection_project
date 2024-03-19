1.Subject?
=========
배송 로봇이 택배 상자에 적힌 qr 코드를 인식하여 주소 정보를 받아 sql에 저장 후 YOLO를
이용한 엘리베이터 버튼 인식

2.QR code detection
===================
(file:///home/chanmin/AA/pic_deep/Screenshot%20from%202024-03-20%2005-43-38.png)







실행 방법
-------

1.<https://drive.google.com/file/d/1kThYxswRs4MMEy2R3CGGIwgP8mm6OcHz/view?usp=share_link> 에서 best_ckpt.pt 파일을 다운로드
  
2.best_ckpt.pt 파일을 deeplearning_project 폴더에 붙여넣기

3.vscode로 detect copy.py 파일 실행

4.카메라가 실행 후 6.png 사진을 비추면 학습된 버튼과 거리가 인식

5.카메라가 켜지지 않으면 코드에서 ctrl + f 를 누르고, dev/cam1 에서의 1을 0으로 변경, 또는 사용자 환경에 맞게 변경

시연 영상
-------
<https://youtu.be/wz1IoBTvRQg>

<https://youtu.be/mXR7-V8i5GE>

<https://youtu.be/B2jjOyeSFAs>

<https://youtu.be/lAegAs4kWWk>
