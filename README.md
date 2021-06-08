# Kubernetes

- เรียกสั่นๆว่า k8s หรือ kube


#### node

- node คือ virtual machine หรือ virtual instance
- node สามารถมีได้หลาย pods

#### pod
- Pod เปรียบเสมือน host ที่สามารถมีหลายได้หลายๆ port
- ทุกๆ pod จะมี ip address ที่ไม่ซ้ำกัน
- IP address เข้าถึงได้จาก Pod อื่นๆ ทั้งหมดใน K8S Cluster
