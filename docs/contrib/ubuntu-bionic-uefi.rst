Danube Cloud :: Factory :: Appliances :: Ubuntu Bionic (18.04)
#############################################################

Minimal `Ubuntu cloud image <https://cloud-images.ubuntu.com/bionic/current/>`__ with support for initialization through `Cloud-init <https://cloudinit.readthedocs.io/>`__.

The image supports following metadata:

* **root_authorized_keys**: content for ``/root/.ssh/authorized_keys``.
* **cloud-init** modules: growpart, resizefs, ssh, set-passwords, etc. For full module list see `cloud-init docs <https://cloudinit.readthedocs.io/en/latest/topics/modules.html>`__.
* **hostname**: Full hostname to be configured by `cloud-init <https://cloudinit.readthedocs.io/>`__ at first boot.

**Note:** To use this image, you need to set *hypervisor type* to ``BHYVE`` and *bootrom* to ``UEFI``.

