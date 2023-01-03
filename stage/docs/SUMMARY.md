# Table of contents

* [Intro to Akash](README.md)
  * [Technical Support](support.md)
  * [Stack Definition Language (SDL)](stack-definition-language.md)
* [Tokens and Wallets](tokens-and-wallets/README.md)
  * [Developer Tokens](token/funding.md)
  * [Buy Akash Tokens](token/buy.md)
  * [Keplr Wallet](token/keplr.md)
  * [Mixin Messenger for AKT](deploy/mixin-messenger-for-akt.md)
* [Deployments](guides/README.md)
  * [Desktop App](guides/deploy/README.md)
    * [Cloudmos Deploy Installation](guides/deploy/cloudmos-deploy-installation.md)
    * [Initial Configuration](guides/deploy/initial-configuration.md)
    * [WordPress Deployment Example](guides/deploy/wordpress-deployment-example.md)
    * [Manage Deployments](guides/deploy/manage-deployments.md)
    * [Custom RPC Node](guides/deploy/custom-rpc-node.md)
  * [CLI](guides/cli/README.md)
    * [Detailed Steps](other-resources/experimental/mainnet4-upgrade-docs/detailed-steps/README.md)
      * [Install Akash CLI](other-resources/experimental/mainnet4-upgrade-docs/detailed-steps/part-1.-install-akash.md)
      * [Create an Account](other-resources/experimental/mainnet4-upgrade-docs/detailed-steps/part-2.-create-an-account.md)
      * [Fund your Account](other-resources/experimental/mainnet4-upgrade-docs/detailed-steps/part-3.-fund-your-account.md)
      * [Configure your Network](other-resources/experimental/mainnet4-upgrade-docs/detailed-steps/part-4.-configure-your-network.md)
      * [Create your Configuration](other-resources/experimental/mainnet4-upgrade-docs/detailed-steps/part-5.-create-your-configuration.md)
      * [Create your Certificate](other-resources/experimental/mainnet4-upgrade-docs/detailed-steps/part-6.-create-your-certificate.md)
      * [Create your Deployment](other-resources/experimental/mainnet4-upgrade-docs/detailed-steps/part-7.-create-your-deployment.md)
      * [View your Bids](other-resources/experimental/mainnet4-upgrade-docs/detailed-steps/part-8.-view-your-bids.md)
      * [Create a Lease](other-resources/experimental/mainnet4-upgrade-docs/detailed-steps/part-9.-create-a-lease.md)
      * [Send the Manifest](other-resources/experimental/mainnet4-upgrade-docs/detailed-steps/part-10.-send-the-manifest.md)
      * [Update the Deployment](other-resources/experimental/mainnet4-upgrade-docs/detailed-steps/part-11.-update-the-deployment.md)
      * [Close Deployment](other-resources/experimental/mainnet4-upgrade-docs/detailed-steps/close-deployment.md)
    * [Akash CLI Booster](guides/cli/akash-cli-booster/README.md)
      * [Getting Started with the CLI Booster](guides/cli/akash-cli-booster/getting-started-with-the-cli-booster.md)
      * [Creating a Deployment with the CLI Booster](guides/cli/akash-cli-booster/creating-a-deployment-with-the-cli-booster.md)
      * [Close a Deployment](guides/cli/akash-cli-booster/close-a-deployment.md)
      * [List All Active Deployments](guides/cli/akash-cli-booster/list-all-active-deployments.md)
      * [Access a Deployment’s Shell](guides/cli/akash-cli-booster/access-a-deployments-shell.md)
      * [Obtain a Deployment’s Logs](guides/cli/akash-cli-booster/obtain-a-deployments-logs.md)
  * [Apps on Akash](guides/apps-on-akash.md)
* [Integrations](deploy/README.md)
  * [TLS Termination of Akash Deployments](deploy/tls-termination-of-akash-deployments/README.md)
    * [Prerequisites](deploy/tls-termination-of-akash-deployments/prerequisites.md)
    * [Akash with TLS Example](deploy/tls-termination-of-akash-deployments/akash-with-tls-example.md)
    * [Find IP Address of Deployment](deploy/tls-termination-of-akash-deployments/find-ip-address-of-deployment.md)
    * [Cloudflare Configuration](deploy/tls-termination-of-akash-deployments/cloudflare-configuration.md)
    * [Verify HTTPS](deploy/tls-termination-of-akash-deployments/verify-https.md)
    * [Troubleshooting](deploy/tls-termination-of-akash-deployments/troubleshooting.md)
  * [Chia on Akash](deploy/chia-on-akash.md)
  * [Polygon on Akash](deploy/polygon-on-akash.md)
  * [Mine Raptoreum on Akash Network](deploy/mine-raptoreum-on-akash-network.md)
  * [Unstoppable Web 2.0](deploy/unstoppable-web-2.0.md)
  * [Multi-Tiered Deployment](deploy/multi-tier-app.md)
  * [Helium Validator](deploy/helium-validator.md)
  * [PostgreSQL restore/backup](deploy/postgresql-restore-backup.md)
  * [Ruby on Rails with Sia and Auth0](deploy/ruby-on-rails-with-sia-and-auth0.md)
* [Providers](providers/README.md)
  * [Build a Cloud Provider](providers/build-a-cloud-provider/README.md)
    * [Kubernetes Cluster for Akash Providers](providers/build-a-cloud-provider/kubernetes-cluster-for-akash-providers/README.md)
      * [STEP 1 - Clone the Kubespray Project](providers/build-a-cloud-provider/kubernetes-cluster-for-akash-providers/step-1-clone-the-kubespray-project.md)
      * [STEP 2 - Install Ansible](providers/build-a-cloud-provider/kubernetes-cluster-for-akash-providers/step-2-install-ansible.md)
      * [STEP 3 - Ansible Access to Kubernetes Cluster](providers/build-a-cloud-provider/kubernetes-cluster-for-akash-providers/step-3-ansible-access-to-kubernetes-cluster.md)
      * [STEP 4 - Ansible Inventory](providers/build-a-cloud-provider/kubernetes-cluster-for-akash-providers/step-4-ansible-inventory.md)
      * [STEP 5 - Additional Verifications/Config](providers/build-a-cloud-provider/kubernetes-cluster-for-akash-providers/step-5-enable-gvisor.md)
      * [STEP 6 - Provider Ephemeral Storage Config (OPTIONAL)](providers/build-a-cloud-provider/kubernetes-cluster-for-akash-providers/step-6-provider-ephemeral-storage-config.md)
      * [STEP 7 - Create Kubernetes Cluster](providers/build-a-cloud-provider/kubernetes-cluster-for-akash-providers/step-6-create-kubernetes-cluster.md)
      * [STEP 8 - Confirm Kubernetes Cluster](providers/build-a-cloud-provider/kubernetes-cluster-for-akash-providers/step-7-confirm-kubernetes-cluster.md)
      * [STEP 9 - Review Firewall Policies](providers/build-a-cloud-provider/kubernetes-cluster-for-akash-providers/step-9-review-firewall-policies.md)
      * [Additional K8s Resources](providers/build-a-cloud-provider/kubernetes-cluster-for-akash-providers/additional-k8s-resources/README.md)
        * [Kubespray Hosts.Yaml Examples](providers/build-a-cloud-provider/kubernetes-cluster-for-akash-providers/additional-k8s-resources/kubespray-hosts.yaml-examples.md)
    * [Akash Cloud Provider Build With Helm Charts](providers/build-a-cloud-provider/akash-cloud-provider-build-with-helm-charts/README.md)
      * [STEP 1 - Prerequisites of an Akash Provider](providers/build-a-cloud-provider/akash-cloud-provider-build-with-helm-charts/step-1-prerequisites-of-an-akash-provider.md)
      * [STEP 2 - Kubernetes Configurations](providers/build-a-cloud-provider/akash-cloud-provider-build-with-helm-charts/step-2-kubernetes-configurations.md)
      * [STEP 3 - Export Provider Wallet](providers/build-a-cloud-provider/akash-cloud-provider-build-with-helm-charts/step-3-export-provider-wallet.md)
      * [STEP 4 - Helm Installation on Kubernetes Node](providers/build-a-cloud-provider/akash-cloud-provider-build-with-helm-charts/step-4-helm-installation-on-kubernetes-node.md)
      * [Step 5 - Domain Name Review](providers/build-a-cloud-provider/akash-cloud-provider-build-with-helm-charts/step-5-domain-name-review.md)
      * [STEP 6 - Provider Build via Helm Chart](providers/build-a-cloud-provider/akash-cloud-provider-build-with-helm-charts/step-6-provider-build-via-helm-chart.md)
      * [STEP 7 - Provider Bid Customization](providers/build-a-cloud-provider/akash-cloud-provider-build-with-helm-charts/step-6-provider-bid-customization.md)
      * [Step 8 - Hostname Operator Build](providers/build-a-cloud-provider/akash-cloud-provider-build-with-helm-charts/step-7-hostname-operator-build.md)
      * [STEP 9 - Ingress Controller Install](providers/build-a-cloud-provider/akash-cloud-provider-build-with-helm-charts/step-8-ingress-controller-install.md)
      * [Step 10 - Firewall Rule Review](providers/build-a-cloud-provider/akash-cloud-provider-build-with-helm-charts/step-9-firewall-rule-review.md)
    * [Akash Provider Checkup](providers/build-a-cloud-provider/akash-provider-checkup/README.md)
      * [Prerequisites](providers/build-a-cloud-provider/akash-provider-checkup/prerequisites.md)
      * [STEP 1 - Launch a Test Deployment on Provider](providers/build-a-cloud-provider/akash-provider-checkup/step-1-launch-a-test-deployment-on-provider.md)
      * [STEP 2 - Inbound Communication Verifications](providers/build-a-cloud-provider/akash-provider-checkup/step-2-inbound-communication-verifications.md)
      * [STEP 3 - Shell Access Verification](providers/build-a-cloud-provider/akash-provider-checkup/step-3-shell-access-verification.md)
      * [STEP 4 - Provider DNS Verification](providers/build-a-cloud-provider/akash-provider-checkup/step-4-provider-dns-verification.md)
      * [STEP 5 - Provider Logs](providers/build-a-cloud-provider/akash-provider-checkup/step-5-provider-logs.md)
      * [STEP 6 - Verify Current Provider Settings](providers/build-a-cloud-provider/akash-provider-checkup/step-6-verify-current-provider-settings.md)
      * [STEP 7 - Additional Verifications](providers/build-a-cloud-provider/akash-provider-checkup/step-6-additional-verifications.md)
      * [Contact Technical Support](providers/build-a-cloud-provider/akash-provider-checkup/contact-technical-support.md)
    * [IP Leases - Provider Enablement (Optional Step)](other-resources/experimental/mainnet4-upgrade-docs/ip-leases-provider-enablement-optional-step/README.md)
      * [Akash Provider Update](other-resources/experimental/mainnet4-upgrade-docs/ip-leases-provider-enablement-optional-step/akash-provider-update.md)
      * [IP Operator](other-resources/experimental/mainnet4-upgrade-docs/ip-leases-provider-enablement-optional-step/ip-operator.md)
      * [Create the MetalLB Namespace](other-resources/experimental/mainnet4-upgrade-docs/ip-leases-provider-enablement-optional-step/create-the-metallb-namespace.md)
      * [MetalLB Install](other-resources/experimental/mainnet4-upgrade-docs/ip-leases-provider-enablement-optional-step/metallb-install.md)
      * [Enable strictARP in kube-proxy](other-resources/experimental/mainnet4-upgrade-docs/ip-leases-provider-enablement-optional-step/enable-strictarp-in-kube-proxy.md)
      * [Additional notes on the IP Operator](other-resources/experimental/mainnet4-upgrade-docs/ip-leases-provider-enablement-optional-step/additional-notes-on-the-ip-operator.md)
    * [Helm Based Provider Persistent Storage Enablement](providers/build-a-cloud-provider/helm-based-provider-persistent-storage-enablement/README.md)
      * [Persistent Storage Requirements](providers/build-a-cloud-provider/helm-based-provider-persistent-storage-enablement/persistent-storage-requirements.md)
      * [Environment Review](providers/build-a-cloud-provider/helm-based-provider-persistent-storage-enablement/environment-review.md)
      * [Storage Class Types](providers/build-a-cloud-provider/helm-based-provider-persistent-storage-enablement/storage-class-types.md)
      * [Deploy Persistent Storage](providers/build-a-cloud-provider/helm-based-provider-persistent-storage-enablement/deploy-persistent-storage.md)
      * [Check Persistent Storage Health](providers/build-a-cloud-provider/helm-based-provider-persistent-storage-enablement/check-persistent-storage-health.md)
      * [Provider Attributes and Pricing Adjustments](providers/build-a-cloud-provider/helm-based-provider-persistent-storage-enablement/provider-attributes-and-pricing-adjustments.md)
      * [Label Nodes For Storage Classes](providers/build-a-cloud-provider/helm-based-provider-persistent-storage-enablement/label-nodes-for-storage-classes.md)
      * [Inventory Operator](providers/build-a-cloud-provider/helm-based-provider-persistent-storage-enablement/inventory-operator.md)
      * [Verifications](providers/build-a-cloud-provider/helm-based-provider-persistent-storage-enablement/verifications.md)
      * [Teardown](providers/build-a-cloud-provider/helm-based-provider-persistent-storage-enablement/teardown.md)
    * [Akash Provider Bid Pricing](providers/build-a-cloud-provider/akash-provider-bid-pricing/README.md)
      * [Download Git Repository](providers/build-a-cloud-provider/akash-provider-bid-pricing/download-git-repository.md)
      * [Run Provider Pricing Calc](providers/build-a-cloud-provider/akash-provider-bid-pricing/run-provider-pricing-calc.md)
      * [Script Execution Templates](providers/build-a-cloud-provider/akash-provider-bid-pricing/script-execution-templates.md)
      * [Example Command Use](providers/build-a-cloud-provider/akash-provider-bid-pricing/example-command-use.md)
  * [Akash Provider FAQ/Troubleshooting](providers/akash-provider-troubleshooting/README.md)
    * [How to terminate the workload from the Akash Provider using CLI](providers/akash-provider-troubleshooting/how-to-terminate-the-workload-from-the-akash-provider-using-cli.md)
    * [Provider Logs](providers/akash-provider-troubleshooting/provider-logs.md)
    * [Provider Status and General Info](providers/akash-provider-troubleshooting/provider-status-and-general-info.md)
    * [Provider Lease Management](providers/akash-provider-troubleshooting/provider-lease-management.md)
    * [Provider Manifests](providers/akash-provider-troubleshooting/provider-manifests.md)
    * [Provider Earnings](providers/akash-provider-troubleshooting/provider-earnings.md)
    * [Dangling Deployments](providers/akash-provider-troubleshooting/dangling-deployments.md)
  * [Community Solutions](providers/community-solutions/README.md)
    * [Praetor](providers/community-solutions/praetor.md)
  * [Custom Kubernetes Cluster Settings](providers/custom-kubernetes-cluster-settings/README.md)
    * [VMware Tanzu](providers/custom-kubernetes-cluster-settings/vmware-tanzu.md)
  * [Akash Audited Attributes](providers/akash-audited-attributes.md)
* [Akash Nodes](akash-nodes/README.md)
  * [Akash Node Via Helm Charts](akash-nodes/akash-node-via-helm-charts/README.md)
    * [Prepare Kubernetes Cluster](akash-nodes/akash-node-via-helm-charts/prepare-kubernetes-cluster.md)
    * [Akash Node Installation](akash-nodes/akash-node-via-helm-charts/akash-node-installation.md)
    * [Node Verifications](akash-nodes/akash-node-via-helm-charts/node-verifications.md)
  * [Akash Node Deployment Via Omnibus](operations/akash-node-deployment-via-omnibus.md)
  * [Akash Node CLI Build](akash-nodes/run-an-akash-node/README.md)
    * [STEP1 - Install Akash Software](akash-nodes/run-an-akash-node/step1-install-akash-software.md)
    * [STEP2 - Add Akash Install Location in the User’s Path](akash-nodes/run-an-akash-node/step2-add-akash-install-location-in-the-users-path.md)
    * [STEP3 - Choose a Node Moniker](akash-nodes/run-an-akash-node/step3-choose-a-node-moniker.md)
    * [STEP4 - Initialize New Node](akash-nodes/run-an-akash-node/step4-initialize-new-node.md)
    * [STEP5 - Set Minimum Gas Price](akash-nodes/run-an-akash-node/step5-set-minimum-gas-price.md)
    * [STEP6 - Copy the Genesis File](akash-nodes/run-an-akash-node/step6-copy-the-genesis-file.md)
    * [STEP7 - Add Seed and Peer Nodes](akash-nodes/run-an-akash-node/step7-add-seed-and-peer-nodes.md)
    * [STEP8 - Fast Sync](akash-nodes/run-an-akash-node/step8-fast-sync.md)
    * [STEP9 - Blockchain Snapshot Use](akash-nodes/run-an-akash-node/step9-blockchain-snapshot-use.md)
    * [STEP10 - Start the Akash Node](akash-nodes/run-an-akash-node/step10-start-the-akash-node.md)
    * [Additional Information](akash-nodes/run-an-akash-node/additional-information.md)
    * [RPC Service](akash-nodes/run-an-akash-node/rpc-service.md)
    * [API Service](akash-nodes/run-an-akash-node/api-service.md)
  * [Public RPC Nodes](akash-nodes/public-rpc-nodes.md)
  * [API Endpoints](akash-nodes/api-endpoints.md)
* [Validating](validating/README.md)
  * [Running a Validator](operations/validator.md)
  * [Akash Validator with TMKMS and Stunnel](validating/akash-validator-with-tmkms-and-stunnel/README.md)
    * [Additional Resources](validating/akash-validator-with-tmkms-and-stunnel/additional-resources.md)
    * [Validator Topology](validating/akash-validator-with-tmkms-and-stunnel/validator-topology.md)
    * [Obtain Private Key](validating/akash-validator-with-tmkms-and-stunnel/obtain-private-key.md)
    * [Akash Validator Deployment](validating/akash-validator-with-tmkms-and-stunnel/akash-validator-deployment.md)
    * [TMKMS Setup](validating/akash-validator-with-tmkms-and-stunnel/tmkms-setup.md)
    * [Start and Verify the TMKMS Service](validating/akash-validator-with-tmkms-and-stunnel/start-and-verify-the-tmkms-service.md)
    * [Stunnel Client](validating/akash-validator-with-tmkms-and-stunnel/stunnel-client.md)
    * [Verify Validator Status](validating/akash-validator-with-tmkms-and-stunnel/verify-validator-status.md)
  * [Akash Validator Using Omnibus](validating/akash-validator-using-omnibus/README.md)
    * [Cloudmos Deploy Review](validating/akash-validator-using-omnibus/cloudmos-deploy-review.md)
    * [FileBase Buckets](validating/akash-validator-using-omnibus/filebase-buckets.md)
    * [Akash SDL Review](validating/akash-validator-using-omnibus/akash-sdl-review.md)
    * [Cloudmos Initial Deployment](validating/akash-validator-using-omnibus/cloudmos-initial-deployment.md)
    * [Edit SDL with Known IDs](validating/akash-validator-using-omnibus/edit-sdl-with-known-ids.md)
    * [Redeploy Validator and Sentries with Cloudmos](validating/akash-validator-using-omnibus/redeploy-validator-and-sentries-with-cloudmos.md)
    * [Validator Verifications](validating/akash-validator-using-omnibus/validator-verifications.md)
* [Command Line](command-line/README.md)
  * [Install Akash](other-resources/experimental/mainnet4-upgrade-docs/install.md)
  * [Setup your Environment](other-resources/experimental/mainnet4-upgrade-docs/shell-variables.md)
  * [Create Your Account](other-resources/experimental/mainnet4-upgrade-docs/wallet.md)
  * [CLI Commands](command-line/cli-commands.md)
* [Features](features/README.md)
  * [IP Leases](other-resources/experimental/ip-leases/README.md)
    * [IP Leases Features and Limitations](other-resources/experimental/ip-leases/ip-leases-features-and-limitations.md)
    * [IP Leases within SDL](other-resources/experimental/ip-leases/ip-leases-within-sdl.md)
    * [IP Leases Port Use](other-resources/experimental/ip-leases/ip-leases-port-use.md)
    * [IP Leases Verification](other-resources/experimental/ip-leases/ip-leases-verification.md)
    * [IP Leases Migration](other-resources/experimental/ip-leases/ip-leases-migration.md)
    * [Full SDL Example with IP Leases](other-resources/experimental/ip-leases/full-sdl-example-with-ip-leases.md)
  * [Persistent Storage](features/persistent-storage/README.md)
    * [Persistent Storage Limitations](features/persistent-storage/persistent-storage-limitations.md)
    * [Implementation Overview](features/persistent-storage/implementation-overview.md)
    * [Persistent Storage SDL Deepdive](features/persistent-storage/persistent-storage-sdl-deepdive.md)
    * [Troubleshooting](features/persistent-storage/troubleshooting.md)
    * [Complete Persistent Storage Manifest/SDL Example](features/persistent-storage/complete-persistent-storage-manifest-sdl-example.md)
  * [Authorized Spend](features/authorized-spend/README.md)
    * [Relevant Commands and Example Use](features/authorized-spend/relevant-commands-and-example-use.md)
  * [Fractional uAKT](features/fractional-uakt/README.md)
    * [Relevant SDL Declaration and Example Use](features/fractional-uakt/relevant-sdl-declaration-and-example-use.md)
  * [Deployment Shell Access](features/deployment-shell-access.md)
  * [Deployment HTTP Options](features/deployment-http-options.md)
  * [Hostname Migration](features/hostname-migration.md)
* [Upgrades](upgrades/README.md)
  * [Akash Mainnet5 Node Upgrade Guide](upgrades/v0.20.0-upgrade-docs.md)
* [Mainnet5 Upgrade Docs](mainnet5-upgrade-docs/README.md)
  * [Provider Upgrade](mainnet5-upgrade-docs/provider-upgrade.md)
* [Other Resources](other-resources.md)
  * [Experimental](other-resources/experimental/README.md)
    * [Omnibus](other-resources/experimental/omnibus/README.md)
      * [Akash Validator with TMKMS](other-resources/experimental/omnibus/akash-validator-with-tmkms/README.md)
        * [Validator Topology](other-resources/experimental/omnibus/akash-validator-with-tmkms/validator-topology.md)
        * [Obtain Private Key](other-resources/experimental/omnibus/akash-validator-with-tmkms/obtain-private-key.md)
        * [Akash Validator Deployment](other-resources/experimental/omnibus/akash-validator-with-tmkms/akash-validator-deployment.md)
        * [TMKMS Setup](other-resources/experimental/omnibus/akash-validator-with-tmkms/tmkms-setup.md)
        * [Start and Verify the TMKMS Service](other-resources/experimental/omnibus/akash-validator-with-tmkms/start-and-verify-the-tmkms-service.md)
    * [Akash Provider Attribute Updates](other-resources/experimental/akash-provider-attribute-updates.md)
    * [Hardware and Software Recommendations](other-resources/experimental/hardware-and-software-recommendations.md)
    * [Streamlined Steps](other-resources/experimental/streamlined-steps/README.md)
      * [Install the Akash CLI](other-resources/experimental/streamlined-steps/install-the-akash-client.md)
      * [Initialize Environment Variables](other-resources/experimental/streamlined-steps/initialize-environment-variables.md)
      * [Create Akash Account and Certificate](other-resources/experimental/streamlined-steps/create-akash-account-and-certificate.md)
      * [Create Test Deployment](other-resources/experimental/streamlined-steps/create-test-deployment.md)
      * [Initialize Deployment Variables](other-resources/experimental/streamlined-steps/initialize-deployment-variables.md)
      * [Review Bids](other-resources/experimental/streamlined-steps/review-bids.md)
      * [Upload Manifest](other-resources/experimental/streamlined-steps/upload-manifest.md)
      * [Close Deployment](other-resources/experimental/streamlined-steps/close-deployment.md)
    * [Akash Deployments via Terraform](other-resources/experimental/akash-deployments-via-terraform/README.md)
      * [Prerequisites](other-resources/experimental/akash-deployments-via-terraform/prerequisites.md)
      * [Terraform Manifest - Template](other-resources/experimental/akash-deployments-via-terraform/terraform-manifest-template.md)
      * [Akash SDL Hello World Example](other-resources/experimental/akash-deployments-via-terraform/akash-sdl-hello-world-example.md)
      * [Create Akash Deployment](other-resources/experimental/akash-deployments-via-terraform/create-akash-deployment.md)
      * [Close Akash Deployment](other-resources/experimental/akash-deployments-via-terraform/close-akash-deployment.md)
      * [Terraform Manifest - Complete Example](other-resources/experimental/akash-deployments-via-terraform/terraform-manifest-complete-example.md)
  * [Security](glossary/security.md)
  * [Containers](glossary/platform.md)
  * [Marketplace](glossary/marketplace.md)
  * [Payments](glossary/escrow.md)
  * [Authentication](glossary/mtls.md)
  * [Archived Resources](other-resources/archived-resources/README.md)
    * [Akash Provider Services v0.1.0 CLI Release Notes](other-resources/archived-resources/akash-v0.18.0-cli-release-notes.md)
    * [Build a Cloud Provider](other-resources/archived-resources/build-a-cloud-provider/README.md)
      * [Kubernetes Cluster](other-resources/archived-resources/build-a-cloud-provider/kubernetes-cluster.md)
      * [gVisor Issue - No system-cgroup v2 Support](other-resources/archived-resources/build-a-cloud-provider/gvisor-issue-no-system-cgroup-v2-support.md)
      * [Provider Networks](other-resources/archived-resources/build-a-cloud-provider/provider-networks.md)
    * [Provider Upgrade](other-resources/archived-resources/provider-upgrade.md)