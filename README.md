# Mastering ServiceNow Scripting
This is the code repository for [Mastering ServiceNow Scripting](https://www.packtpub.com/virtualization-and-cloud/mastering-servicenow-scripting?utm_source=github&utm_medium=repository&utm_content=9781788627092), published by [Packt](https://www.packtpub.com/?utm_source=github). It contains all the supporting project files necessary to work through the book from start to finish.
## About the Book
ServiceNow is gradually evolving as the platform of choice for IT Service management. Industry giants such as RedHat and NetApp have adopted ServiceNow for their operational needs. ServiceNow provides clients with an extra add-on when it comes to their baseline instances, as scripting can be used to customize and improve the performance of their instances. ServiceNow provides inbuilt JavaScript API for scripting and improving an instance using JavaScript.

This book will initially cover the basics of ServiceNow scripting and the appropriate time to script in a ServiceNow environment. Then, we will dig deeper into client-side and server-side scripting using JavaScipt API. We will also cover advanced concepts such as on-demand functions, script actions, and best practices. This book will act as an end-to-end guide to writing, testing, and debugging scripts in ServiceNow. We will also cover update sets for moving customizations between ServiceNow instances, Jelly scripts for making custom pages, and best practices for all types of script in ServiceNow.

At the end of this book, you will have hands-on experience of scripting in ServiceNow using the inbuilt JavaScript API.
## Instructions and Navigation
All of the code is organized into folders. Each folder starts with a number followed by the application name. For example, Chapter02.

The code will look like the following:
```
function onChange(control, oldValue, newValue, isLoading, isTemplate) {
    if (isLoading || newValue === '') {
        return;
    }

    //Type appropriate comment here, and begin script below

}
```
## Hardware and Software Requirements

The OpenStack installation will require the following hardware specifications:
* A host machine with CPU hardware virtualization support
* 8 CPU cores
* 16 GB RAM
* 60 GB free disk space

The lab environment uses the following software and tools:
* Operating system: CentOS 7 or Ubuntu 14.04
* OpenStack: Mitaka and later releases
* VirtualBox 5.0 or newer
* Vagrant 2.0.1 or newer
* Ansible server 2.4 or newer
* Python 2.7


## Related Products
* [ServiceNow Cookbook - Second Edition](https://www.packtpub.com/virtualization-and-cloud/servicenow-cookbook-second-edition?utm_source=github&utm_medium=repository&utm_content=9781788834056)

* [OpenStack Cloud Computing Cookbook - Fourth Edition](https://www.packtpub.com/virtualization-and-cloud/openstack-cloud-computing-cookbook-fourth-edition?utm_source=github&utm_medium=repository&utm_content=9781788396110)

* [OpenStack: Building a Cloud Environment](https://www.packtpub.com/virtualization-and-cloud/openstack-building-cloud-environment?utm_source=github&utm_medium=repository&utm_content=9781788396110)
