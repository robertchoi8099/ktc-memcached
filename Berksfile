#
# vim: set ft=ruby:
#
site :opscode

metadata

cookbook 'ktc-etcd', github: 'cloudware-cookbooks/ktc-etcd', branch: 'develop'
cookbook 'ktc-utils', github: 'cloudware-cookbooks/ktc-utils', branch: 'develop'
# until they cut a realease that fixes this bug:
# https://github.com/opscode-cookbooks/memcached/commit/d527134987d4e53bb86bd2319b1f1cbf8171355a
cookbook 'memcached', github: 'opscode-cookbooks/memcached'
cookbook 'openstack-block-storage', github: 'stackforge/cookbook-openstack-block-storage'
cookbook "openstack-common", github: "stackforge/cookbook-openstack-common"
cookbook "openstack-identity", github: "stackforge/cookbook-openstack-identity"
cookbook "openstack-image", github: "stackforge/cookbook-openstack-image"
cookbook 'openstack-object-storage', github: 'stackforge/cookbook-openstack-object-storage'
cookbook 'services', github: 'spheromak/services-cookbook'

group :integration do
  cookbook 'ktc-testing', path: "../ktc-testing"
  cookbook 'ubuntu'
end
