# Cloudmesh Compute Project for Google Cloud Platform (GCP)

Harshawardhan Pandit, [fa19-516-165](https://github.com/cloudmesh-community/fa19-516-169)

## Abstract

Cloudmesh enables you to access multi-cloud environments such as AWS,
Azure, Google, and OpenStack Cloudsvery easily. The purpose of this
project is to implement identified features for the **Google Cloud
Platform**.  The two cloud interface will be implemented using:

1. Google Cloud Platform
1. AWS

Selected APIs will be added for the following features:

1. Images
1. Flavors
1. Virtual machines
1. Keys
1. Security groups

## Architecture

![Architecture](https://github.com/cloudmesh-community/fa19-516-169/blob/master/project/images/Architecture.png)

## APIs

Typical List of APIS to be developed may include in the follow
categories:

### VM

1. start
1. reboot
1. stop
1. resume
1. suspend
1. info
1. status
1. list
1. create
1. create_vm_parameters

### Flavors

1. flavors
1. flavor

### image

1. image

### keys

1. keys
1. key_uplo
1. key_delete

### Security groups

1. ssh
1. get_resource_group
1. set_server_metadata
1. delete_server_metadata
1. list_secgroups
1. list_secgroup_rules
1. add_secgroup
1. add_secgroup_rule
1. remove_secgroup
1. upoad_secgroup
1. add_rules_to_secgroup
1. remove_rules_from_secgroup

## Technologies

* Python 3.7.4
* REST API
* Cloudmesh

## Progress

### Week of 22nd Sep

* Project Definition and approval

### Week of 7th Oct

* Rest API ramp up

### Week of 14th Oct

* Cloudmesh Installation on Windows. Solving the laptop
  issues and finally succeeded in Cloudmesh installation on
  Windows 10 environment.

### Week of 21st Oct

* Study of existing Cloudmesh Compute Project/source code structure.
* Initial Architecture Diagram (In Progress).
* Listing down potential APIs for Cloudmesh Compute GCP Interface.
* Initial study of [Compute Engine API](https://cloud.google.com/compute/docs/reference/rest/v1/) from Google.
* Creation of WBS. Plan.

## Work Breakdown Structure

This is intended WBS and schedule. This can change as we proceed as the
proposed plan below and will evolve.

1. Week of 28th Oct: Architecture, Design finalization.
1. Week of 4th Nov:

* API signature definition and scope freeze (This should define how
  many APIs will be)
* Environment creation and Code Framework Creation (Skeleton, stub
  and dummy test cases)

1. Week of 11th Nov:  Selected APIs for VM
1. Week of 18th Nov:  Selected APIs for Image
1. Week of 25th Nov:  Selected APIs for Security
1. Week of 2nd Dec:

   * Buffer
   * Documentation completion
   * Pending PyTest (if any) completion

## Results

## Benchmark

TBD Benchmarking will be added as the interfaces are defined

## Testing

TBD Pytests will be added to the interfaces, as the APIs are developed.

## References

1. <https://cloudmesh.github.io/cloudmesh-manual/projects/project-compute.html>
1. <https://github.com/cloudmesh/cloudmesh-cloud/tree/master/cloudmesh/compute>
