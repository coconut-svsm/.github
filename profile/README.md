# COCONUT-SVSM

COCONUT-SVSM (the COCONUT Secure VM Service Module) is a project under the [Confidential Computing Consortium](https://confidentialcomputing.io/). It provides secure services and device emulation to guest operating systems in confidential virtual machines. It runs in the guest's trusted context, with current support focused on AMD SEV-SNP and Intel TDX. The main implementation lives in the [SVSM repository](https://github.com/coconut-svsm/svsm).

## Documentation

- [Documentation home](https://coconut-svsm.github.io/svsm/) — project overview and technical documentation.
- [Installation guide](https://coconut-svsm.github.io/svsm/installation/INSTALL/) — build the required host, firmware, QEMU, and SVSM components, then launch a guest.
- [Developer information](https://coconut-svsm.github.io/svsm/developer/CONTRIBUTING/) — contribution process and guidelines. The documentation site's **Developer Information** section also covers testing, debugging, and design topics.
- [Development plan](https://coconut-svsm.github.io/svsm/developer/DEVELOPMENT-PLAN/) — design principles and planned or ongoing work.

## Repositories

| Repository | Purpose |
| --- | --- |
| [svsm](https://github.com/coconut-svsm/svsm) | Main COCONUT-SVSM implementation and documentation. |
| [governance](https://github.com/coconut-svsm/governance) | Project governance, policies, groups, and meeting information. |
| [coconut-alloc](https://github.com/coconut-svsm/coconut-alloc) | Heap allocator used by COCONUT-SVSM. |
| [cocoon-tpm](https://github.com/coconut-svsm/cocoon-tpm) | Rust workspace for a software TPM and related cryptography and storage components. |
| [cpufeature](https://github.com/coconut-svsm/cpufeature) | x86 CPUID feature checking library. |
| [packit](https://github.com/coconut-svsm/packit) | Library and command-line tool for packing filesystems into single blobs. |
| [kbs-test](https://github.com/coconut-svsm/kbs-test) | Test server that mimics a Key Broker Service for SVSM attestation testing. |
| [linux](https://github.com/coconut-svsm/linux) | Linux fork with host kernel support needed to run SVSM guests. |
| [qemu](https://github.com/coconut-svsm/qemu) | QEMU fork for SVSM and IGVM guest launch support. |
| [virtio-drivers](https://github.com/coconut-svsm/virtio-drivers) | Fork of the Rust VirtIO guest drivers. |
| [edk2](https://github.com/coconut-svsm/edk2) | Archived EDK II firmware fork. |
| [ms-tpm-20-ref](https://github.com/coconut-svsm/ms-tpm-20-ref) | Archived TPM 2.0 reference implementation fork. |
| [codeowner-tests](https://github.com/coconut-svsm/codeowner-tests) | Test repository for CODEOWNERS behavior. |

For the current repository list, see the [COCONUT-SVSM GitHub organization](https://github.com/orgs/coconut-svsm/repositories).
