# Cloudmesh Compute Project for  Google Cloud Platform (GCP)

Harshawardhan  Pandit, [fa19-516-165](https://github.com/cloudmesh-community/fa19-516-169)



## Abstract

Cloudmesh enables you to access multi-cloud environments such as AWS,
Azure, Google, and OpenStack Cloudsvery easily. The purpose of this
project is to implement identified features for the **Google Cloud
Platform**.  The two cloud interface will be implemented using:

1. Google Cloud Platform
2. AWS

Selected APIs will be added for the following features:

1. Images
2. Flavors
3. Virtual machines
4. Keys
4. Security groups

## Architecture

![Architecture](https://github.com/cloudmesh-community/fa19-516-169/blob/master/project/images/Architecture.png)

## APIs

Typical List of APIS to be developed may include in the follow categories:

**VM**

1. start
2. reboot
3. stop
4. resume
5. suspend
6. info
7. status
8. list
9. create
10. create_vm_parameters

**Flavors**

1. flavors
2. flavor

**image**

1. image

**keys**

1. keys
2. key_uplo
3. key_delete

**Security groups**

1. ssh
2. get_resource_group
3. set_server_metadata
4. delete_server_metadata
5. list_secgroups
6. list_secgroup_rules
7. add_secgroup
8. add_secgroup_rule
9. remove_secgroup
10. upoad_secgroup
11. add_rules_to_secgroup
12. remove_rules_from_secgroup

## Technologies

* Python 3.7.4
* REST API
* Cloudmesh

## Progress

1. Week of 22nd Sep:
   Project Definition and approval

2. Week of 7th Oct:
   Rest API ramp up

3. Week of 14th Oct:
   Cloudmesh Installation on Windows. Solving the laptop issues and finally succeeded in Cloudmesh installation on
   Windows 10 environment.

4. Week of 21st Oct:

   1. Study of existing Cloudmesh Compute Project/source code structure.
   2. Initial Architecture Diagram (In Progress).
   3. Listing down potential APIs for Cloudmesh Compute GCP Interface.
   4. Initial study of [Compute Engine API](https://cloud.google.com/compute/docs/reference/rest/v1/) from Google.
   5. Creation of WBS. Plan.



## Work Breakdown Structure

This is intended WBS  and schedule. This can change as we proceed as the
proposed plan below and will evolve.

1. Week of 28th Oct: Architecture, Design finalization.

2. Week of 4th Nov:
   
   * API signature definition and scope freeze (This should define how 
     many APIs will be )
   * Environment creation  & Code Framework Creation (Skeleton, stub 
     and dummy test cases)

4. Week of 11th Nov:  Selected APIs for  'VM'

5. Week of 18th Nov:  Selected APIs for 'Image'

6. Week of 25th Nov:  Selected APIs for 'Security'

7. Week of 2nd Dec:

   *   Buffer
   *   Documentation completion
   *   Pending PyTest (if any) completion


## Results

## Benchmark

TBD- Benchmarking will be added as the interfaces are defined

## Testing

TBD- Pytests will be added to the interfaces, as the APIs are developed.

## References

1. <https://cloudmesh.github.io/cloudmesh-manual/projects/project-compute.html>
2. <https://github.com/cloudmesh/cloudmesh-cloud/tree/master/cloudmesh/compute>
