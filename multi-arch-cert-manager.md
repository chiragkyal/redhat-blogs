[toc]

# Manage certificates on OpenShift running on IBM Z®, IBM Power® and ARM64 architectures.


## Intoduction
The cert-manager Operator for Red Hat OpenShift provides a secure and efficient solution for SSL/TLS certificate management in OpenShift Container Platform clusters, by introducing certificates and certificate issuers as primary resources in the Kubernetes API.  This 'certificates as a service' model seamlessly integrates with external certificate authorities, automating the entire certificate lifecycle, from provisioning to renewal, ensuring validity and timely updates.

Now, with the latest update, the cert-manager Operator for Red Hat OpenShift `v1.13.0` has undergone an expansion in its scope. Formerly confined to supporting solely on `AMD64` architecture, it now includes extended support for managing certificates on OpenShift across multiple architectures, including IBM Z® (`s390x`), IBM Power® (`ppc64le`), and `ARM64`. 

In this article, I'll briefly explore multi-arch container images before delving into the process of setting up an OpenShift cluster on IBM Power®. I'll then proceed to the cert-manager Operator installation and demonstrate its use in certificate management. 

It's worth noting that comparable steps can be applied to other supported architectures. I've provided links to relevant documents for further reference.

So, let's begin!



## Multi-arch container image

### How to create one?
### Show manifest for cert-manager








## Create OpenShift cluster on IBM Power VS

## Install cert-manager on IBM Power

## Certificate Management
### How to change the default ingress controller 

## Reference


---
## EXTRA
In this latest update, the cert-manager Operator for Red Hat OpenShift has undergone an expansion in its scope. Previously confined to the OpenShift Container Platform solely on AMD64 architecture, it now encompasses broader support. This includes the management of certificates on OpenShift Container Platform instances running on IBM Z® (s390x), IBM Power® (ppc64le), and ARM64 architectures.


In this latest update, the cert-manager Operator for Red Hat OpenShift has broadened its capabilities. Initially confined to the OpenShift Container Platform on AMD64 architecture, it now extends its support to manage certificates on OpenShift Container Platform across diverse architectures, including IBM Z® (s390x), IBM Power® (ppc64le), and ARM64.


In this latest update, the cert-manager Operator for Red Hat OpenShift has broadened its capabilities. Formerly confined to supporting the OpenShift Container Platform solely on AMD64 architecture, it now includes extended support for managing certificates on OpenShift Container Platform across multiple architectures, including IBM Z® (s390x), IBM Power® (ppc64le), and ARM64.

Reference
- https://docs.openshift.com/container-platform/4.13/security/cert_manager_operator/index.html
- https://developers.redhat.com/articles/2022/07/19/secure-kubernetes-certificates-cert-manager-and-dekorate#
- https://developers.redhat.com/articles/2023/10/25/how-openshift-cert-manager-simplifies-cluster-certificates
- https://docs.openshift.com/container-platform/4.14/security/cert_manager_operator/cert-manager-operator-release-notes.html#cert-manager-operator-release-notes-1.13

Other Titles
- cert-manager Operator for Red Hat OpenShift supports multi-architecture systems
- Yes, cert-manager Operator for Red Hat OpenShift supports multi-architecture systems













































---------------------------------

<style>

html, body, .ui-content {
    background-color: #333;
    color: #ddd;
}

.markdown-body h1,
.markdown-body h2,
.markdown-body h3,
.markdown-body h4,
.markdown-body h5,
.markdown-body h6 {
    color: #ddd;
}

.markdown-body h1,
.markdown-body h2 {
    border-bottom-color: #ffffff69;
}

.markdown-body h1 .octicon-link,
.markdown-body h2 .octicon-link,
.markdown-body h3 .octicon-link,
.markdown-body h4 .octicon-link,
.markdown-body h5 .octicon-link,
.markdown-body h6 .octicon-link {
    color: #fff;
}

.markdown-body img {
    background-color: transparent;
}

.ui-toc-dropdown .nav>.active:focus>a, .ui-toc-dropdown .nav>.active:hover>a, .ui-toc-dropdown .nav>.active>a {
    color: white;
    border-left: 2px solid white;
}

.expand-toggle:hover, 
.expand-toggle:focus, 
.back-to-top:hover, 
.back-to-top:focus, 
.go-to-bottom:hover, 
.go-to-bottom:focus {
    color: white;
}


.ui-toc-dropdown {
    background-color: #333;
}

.ui-toc-label.btn {
    background-color: #191919;
    color: white;
}

.ui-toc-dropdown .nav>li>a:focus, 
.ui-toc-dropdown .nav>li>a:hover {
    color: white;
    border-left: 1px solid white;
}

.markdown-body blockquote {
    color: #bcbcbc;
}

.markdown-body table tr {
    background-color: #5f5f5f;
}

.markdown-body table tr:nth-child(2n) {
    background-color: #4f4f4f;
}

.markdown-body code,
.markdown-body tt {
    color: #eee;
    background-color: rgba(230, 230, 230, 0.36);
}

a,
.open-files-container li.selected a {
    color: #5EB7E0;
}

</style>






