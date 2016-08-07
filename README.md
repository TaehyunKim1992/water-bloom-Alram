test.sh 스크립트를  정해진 횟수만큼 반복
 
1. 사진을 찍어 www/final.bmp 저장
2. 컴파일된 C프로그램 실행
3. bmp 분석 및 result.txt 해당 폴더에 저장
4. ds18b20.py (온도측정) 결과 temp.txt 해당 폴더에 저장
5. php에서는 읽어온 temp.txt와 result.txt를 XML형태로 서버에 저장 
