This script allows you to request data from the bazalt api, returns two JSONs, the first with all the packages that are in the sisyphus, but which are not in p10, the second is vice versa.
Optionally made (the algorithm is not optimal, to put it mildly) the output of the third JSON, which contains all packages whose version in sisyphus is higher than in p10, is launched with the flag --force or -f

Force mode is disabled by default, as are click decorators, because there was a conflict in jupyter
