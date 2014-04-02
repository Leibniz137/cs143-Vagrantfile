This is a Vagrantfile for the Stanford/Coursera MOOC on [Compilers](https://class.coursera.org/compilers-004/).

This Vagrantfile uses the official [precise32 boxfile](http://files.vagrantup.com/precise32.box) hosted by [vagrantbox.es](http://www.vagrantbox.es).

During the provisioning process, this vagrantfile GETs the Stanford Compilers CS143 [tar archive](http://spark-university.s3.amazonaws.com/stanford-compilers/vm/student-dist.tar.gz).
This archive is saved /root and extracted to /usr/class/cs143.

I have tried to keep this as straightforward as possible for the end-user.

Keep in mind you are downloading something from the internet.
