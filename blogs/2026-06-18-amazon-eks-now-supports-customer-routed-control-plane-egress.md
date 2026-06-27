---
title: "Amazon EKS now supports customer-routed control plane egress"
url: "https://aws.amazon.com/about-aws/whats-new/2026/06/amazon-eks-customer-routed-control-plane-egress"
date: "2026-06-18"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
Amazon EKS introduces customer-routed control plane egress, letting users direct Kubernetes API server outbound traffic, including admission webhook callbacks, OIDC provider lookups, and API server aggregation requests, through their own VPC. Configuration sets controlPlaneEgressMode to CUSTOMER_ROUTED during cluster creation or updates, with organization-wide enforcement via IAM condition keys.
