1. 해당 파일을 git clone. 위치는 가상머신이 실행되고 있는 OS 안에 할 것.
2. make, make fs.img 그리고
   qemu-system-i386 -nographic -serial mon:stdio -hdb fs.img xv6.img -smp 1 -m 512 실행도 하면 기본 세팅완료.
3. 편하게 실행하기 위해 bootxv6.sh로 생성함.
4. 세팅 완료
