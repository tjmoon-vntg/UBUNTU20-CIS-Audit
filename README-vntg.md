vars 파일 내용 수정해서 필요한 테스트만 돌림

```
# pwd
/vagrant
git clone https://github.com/ansible-lockdown/UBUNTU20-CIS.git
cd UBUNTU20-CIS
export AUDIT_CONTENT_LOCATION="/vagrant"
./run_audit.sh -v vars/test.yml -f rspecish
```
