# NTUAF - Door

## Concept
> �|�D�ηŮ����P�_�A�M�w�v�רs�O�ۤv�ӨëD�L�H�C�b�\�h���X�ڭ��`�n�g�L���A�{�b�A�ڭ̱N�K�W�|�D�M�Ů������Ҧb���W�A���g�L���P�ǡu�M�w�ۤv���ȡv�A�O�n�q�L�|�D���O�H�٬O�q�L�Ů����H�M�w�ۤv��������A�ڭ̱N�H������N���覡�A�����Ѯi�H��ıťı�H�α��ҤW���^�X�A�åB�z�L�۹���ƴ���������ѦҼƾڡA���Ѯi�H�ϫ�ۤv�O�_�p���ܤ��ߪ��n���A�Ӥ��Q�L�H���k�C

# Technique
## Polygraph machine (/lie)
### software
- kinect
	- detect head and body
	- countdown and snapshot

- web
	- slide down question
	- read heartbeat data from file
	- count win/lose score by heartbeat, answer, and time of answering
	- write number of people for each result to firebase
	- composite photo from kinect by an bg image according to the win/lose score (by imagemagick and bat script)
	- upload image to imgur and create qrcode for user to download
	- enable user to login fb and share the composite photo 

### hardware
- heartbeat detector
- notebook, ipad, kinect

## Displayer (/tv)
### software
- web
	- read the sum of people passing winner/loser door
	- get result data from firebase
	- display all statistic data

### hardware
- people entering door detector
- pc, screen

