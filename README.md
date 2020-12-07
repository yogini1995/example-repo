# Useful Links

<a href="https://www.packtpub.com/cloud-networking/cloud-native-with-kubernetes?utm_source=github&utm_medium=repository&utm_campaign=9781786461629"><img src="" alt="Useful Links" height="256px" align="right"></a>

This is the code repository for [Useful Links](https://www.packtpub.com/cloud-networking/cloud-native-with-kubernetes?utm_source=github&utm_medium=repository&utm_campaign=9781786461629), published by Packt.

**Deploy, configure, and run modern cloud native applications on Kubernetes**



This book covers the following exciting features:
* Set up Kubernetes and configure its authentication
* Deploy your applications to Kubernetes
* Configure and provide storage to Kubernetes applications
* Expose Kubernetes applications outside the cluster
* Control where and how applications are run on Kubernetes
Set up observability for Kubernetes
Build a continuous integration and continuous deployment (CI/CD) pipeline for Kubernetes
Extend Kubernetes with service meshes, serverless, and more

If you feel this book is for you, get your [copy](https://www.amazon.com/dp/1838823077) today!

<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" 
alt="https://www.packtpub.com/" border="5" /></a>

## Instructions and Navigations
All of the code is organized into folders. For example, Chapter02.

The code will look like the following:
```
apiVersion: networking.k8s.io/v1
kind: NetworkPolicy
metadata:
 name: full-restriction-policy
 namespace: development
spec:
 policyTypes:
 - Ingress
 - Egress
 podSelector: {}
```

**Following is what you need for this book:**
This book is for developers, architects, DevOps engineers, or anyone interested in developing and managing cloud-native applications. Those already running cloud applications and looking for a better way to manage their platform or others interested in a career change given the recent popularity of Kubernetes will also find this book helpful. Some familiarity with cloud computing, containers and DevOps is required, but no prior knowledge of building production applications using Kubernetes is needed to get started with this book.

With the following software and hardware list you can run all code files present in the book (Chapter 1-15).
### Software and Hardware List
| Chapter | Software required | OS required |
| -------- | ------------------------------------ | ----------------------------------- |
| 1-15 | Docker | Windows, Mac OS X, and Linux (Any) |
| 1-15 | Kubernetes | Can be run locally with Minikube on macOS |
| 1-15 | Helm | Windows, Mac OS X, and Linux (Any) |

We also provide a PDF file that has color images of the screenshots/diagrams used in this book. [Click here to download it](https://static.packt-cdn.com/downloads/9781838823078_ColorImages.pdf).

### Related products
*  [[Packt]](http://www.packtpub.com/product/mastering-kubernetes-third-edition?utm_source=github&utm_medium=repository&utm_campaign=) [[Amazon]](https://www.amazon.com/dp/1839211253)

*  [[Packt]](http://www.packtpub.com/product/kubernetes-and-docker-an-enterprise-guide?utm_source=github&utm_medium=repository&utm_campaign=) [[Amazon]](https://www.amazon.com/dp/183921340X)



## Get to Know the Author
**Alexander Raul**
is CEO of Rackner, an innovative consultancy that builds, runs, and secures Kubernetes and the Cloud for clients ranging from highly funded startups, to Fortune and Global 500 enterprises. With Rackner, he has personally built and managed large Kubernetes-based platforms, and implemented end to end DevSecOps for organizations. Though his background and education is technical (he received an Aerospace Degree from the University of Maryland), he is well versed in the business and strategic arguments for the cloud and Kubernetes - as well as the issues around adoption of these technologies. Alexander lives in Washington, D.C. - and when he isn’t working with clients, he’s mountaineering, skiing, or running marathons.

## Other books by the authors
* * * * * 
