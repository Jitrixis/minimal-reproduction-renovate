# minimal-reproduction-renovate

The actual behavior :
 - renovate set in the dockerfile the latest version of jenkins as of today 2.361.2
 - renovate update the list of plugins as the latest possible
 - Actualy the updated list of plugins is too high for the docker version of jenkins

Expected behavior :
 - Renovate should only update the list of plugins as the latest possible **for the jenkins version**
