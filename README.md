# Panorama Image Stitching
문제 
ORB 디텍터로 특징점 추출

BFMatcher(Hamming 거리) 또는 FLANN 매처로 매칭

RANSAC 기반 호모그래피 추정으로 잘못된 매칭(아웃라이어) 제거

warpPerspective를 이용해 두 이미지를 합성
