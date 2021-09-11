# Học Vagrant

## Giới thiệu

Hỏi: Vagrant để làm gì?

Đáp: Vagrant là một công cụ tương tác với các nền tảng ảo hóa như VirtualBox, HyperV, VM ..., nó giúp tạo và quản lý các máy ảo trên các nền tảng đó. Vagrant cung cấp một cấu hình đơn giản tạo và quản lý, tương tác với máy ảo mà không có nhiều sự khác biệt dù bạn đang sử dụng VirtualBox, VM hay HyperV.

Khi chúng ta muốn giả lập Docker Swarm gồm nhiều máy ảo tham gia hệ thống Swarm nên dùng Vagrant. Có cách thủ công là tạo từng máy ảo nhưng sẽ làm thủ công và không thực hiện lại được nhanh ở môi trường vật lý khác.


Hỏi: Vagrant của công ty nào?

Đáp: Vagrant do Hashi Corp phát triển. Xem [https://www.vagrantup.com/](https://www.vagrantup.com/)

Hỏi: Tài liệu học nhanh Vagrant bằng tiếng Việt

Đáp: [Sử dụng Vagrant tạo và quản lý máy ảo](https://xuanthulab.net/su-dung-vagrant-tao-va-quan-ly-may-ao.html)

Hỏi: Dùng Vagrant để triển khai Docker Swarm như thế nào?

Đáp: Mục đích của chúng ta là dùng Vagrant để tạo ra nhiều máy ảo. Trong mỗi máy ảo sẽ cài môi trường Docker để tạo thành một Docker Swarm. Vậy hãy tham khảo bài viết này [Learn Docker Swarm with Vagrant](https://levelup.gitconnected.com/learn-docker-swarm-with-vagrant-47dd52b57bcc)


## Căn bản Vagrant

Để sử dụng Vagrant cần cài hoặc VirtualBox hoặc VMWare Fusion.

Sử dụng VirtualBox là cách nhanh nhất để khởi động Vagrant.

Còn nếu bạn dùng VMWare Fusion nên cài bản Professional 11.5.3 trên MacOSX High Sierra. Sau đó cài [vagrant-vmware-desktop](https://github.com/hashicorp/vagrant-vmware-desktop) bằng lệnh

```
$ vagrant plugin install vagrant-vmware-desktop
```

Xem chi tiết ở đây [https://www.vagrantup.com/docs/providers/vmware/installation](https://www.vagrantup.com/docs/providers/vmware/installation)

Hãy tham khảo 
1. [Vagrant QuickStart](https://learn.hashicorp.com/tutorials/vagrant/getting-started-index)

## Các bài tutorial trong repo này

1. [Vagrant khởi động máy ảo Ubuntu chứa Nginx web server](Nginx)
2. [Vagrant khởi động máy ảo Ubuntu chứa Docker]
3. [Vagrant khởi động 4 máy ảo Ubutun: 2 Managers, 2 Workers](swarm/ReadMe.md)
