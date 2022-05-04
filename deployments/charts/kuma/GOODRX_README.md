I needed to add our modifications to the kuma helm chart to the kong mesh helm
chart. I downloaded the kong mesh helm chart and applied it's additions to the
kuma helm chart manually. This allows us to deploy using their helm chart, and
if/when they accept our changes into kuma, they'll then accept them into kong
mesh as well, and we can switch to using their native kong mesh helm chart.
