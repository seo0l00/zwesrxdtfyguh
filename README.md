# zwesrxdtfyguh

#준비과정
처음에는 USB카메라를 CSI로 대체하는것부터 시작하였다.
CSI판과 Jetson Nano 2GB Developer Kit를 받아서 하나의 Jetson Nano 2GB Developer로 조립하였다.
NVIDIA에서 제공하는 [Jetson Nano Developer Kit SD Card Image]를 설치하였다.
+ Jetson Nano도 윈도우 OS와 같은 OS를 설치해야합니다.
+ Jetson Nano는 기본 메모리 디스크가 없어서, 별도의 Micro SD 메모리 카드에 다운로드해주없다.
다운 받은 후에는 이미지를 압축해제, SD CARD formatter를 이용하여 포맷을 시킨후 balenaEtcher를 사용하여 포맷한 Micro SD 카드에 미리 다운 받아둔 이미지를 굽고 Micro SD 카드를 Jetson Nano 2GB Developer 조립하였다(이과정에서 오류 발생 및 해결)

# 오류 발생
Micro SD 카드에 미리 다운 받아둔 이미지를 굽는 과정이 원활하게 이루어지지 못해서 8번정도의 시행착오를 경험하였고, 낮은 버전의 이미지를 다운받아 활용하는 방법을 통해서 위에 과정을 시행할수 있었다.
