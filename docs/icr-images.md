
# IBM Container Registry (ICR)

WebSphere Liberty container images are available from IBM Container Registry (ICR) at `icr.io/appcafe/websphere-liberty`. Our recommendation is to use ICR instead of Docker Hub, since ICR doesn't impose rate limits on image pulls. Images can be pulled from ICR without authentication. Only images with Universal Base Image (UBI) as the Operating System are available in ICR at the moment.

The images for the latest release and the last two quarterly releases are available at all times and are refreshed regularly.

Available image tags are listed below. The tags follow this naming convention: 
```
<fixpack_version_optional>-<liberty_image_flavour>-<java_version>-<java_type>-ubi
```

Append a tag to `icr.io/appcafe/websphere-liberty` to pull a specific image. For example, 
```
icr.io/appcafe/websphere-liberty:22.0.0.12-kernel-java17-openj9-ubi
```

Available images can be listed using [IBM Cloud CLI](https://cloud.ibm.com/docs/cli?topic=cli-getting-started). Log in with your IBMid prior to running the following commands. Note that authentication is only required to list the images. **Images can be pulled from ICR without authentication** : 
```
ibmcloud cr region-set global 
ibmcloud cr images --restrict appcafe/websphere-liberty
```


## Latest version

```
kernel-java8-openj9-ubi
kernel-java8-ibmjava-ubi
kernel-java11-openj9-ubi
kernel-java17-openj9-ubi

full-java8-openj9-ubi
full-java8-ibmjava-ubi
full-java11-openj9-ubi
full-java17-openj9-ubi
```

## 22.0.0.13

```
22.0.0.13-kernel-java8-openj9-ubi
22.0.0.13-kernel-java8-ibmjava-ubi
22.0.0.13-kernel-java11-openj9-ubi
22.0.0.13-kernel-java17-openj9-ubi

22.0.0.13-full-java8-openj9-ubi
22.0.0.13-full-java8-ibmjava-ubi
22.0.0.13-full-java11-openj9-ubi
22.0.0.13-full-java17-openj9-ubi
```

## 22.0.0.12

```
22.0.0.12-kernel-java8-openj9-ubi
22.0.0.12-kernel-java8-ibmjava-ubi
22.0.0.12-kernel-java11-openj9-ubi
22.0.0.12-kernel-java17-openj9-ubi

22.0.0.12-full-java8-openj9-ubi
22.0.0.12-full-java8-ibmjava-ubi
22.0.0.12-full-java11-openj9-ubi
22.0.0.12-full-java17-openj9-ubi
```

## 22.0.0.9

```
22.0.0.9-kernel-java8-openj9-ubi
22.0.0.9-kernel-java8-ibmjava-ubi
22.0.0.9-kernel-java11-openj9-ubi
22.0.0.9-kernel-java17-openj9-ubi

22.0.0.9-full-java8-openj9-ubi
22.0.0.9-full-java8-ibmjava-ubi
22.0.0.9-full-java11-openj9-ubi
22.0.0.9-full-java17-openj9-ubi
```
