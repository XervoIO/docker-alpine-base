Modulus Base Alpine Docker Image
=========

The base Docker image for all Modulus alpine images.  Built off of Gliderlabs Alpine image, comes with Bash and OpenSSL installed.

## Volumes

`/mnt`

The volume mounted at `/mnt` requires the follow subdirectories to be created by the host system.

`/mnt/tmp` Temporary storage. The TEMP_DIR environment variable is defined to here.
`/mnt/home` The mop user's home directory. The HOME environment variable is defined to here.

## Usage
The Modulus base image is used like any other image:

```
FROM: onmodulus/alpine-base

# Customizations
```
