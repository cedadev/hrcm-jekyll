---
date: 2020-09-28 14:56:38
description: 'HighResMIP protocol

  The HighResMIP protocol is described in detail in [http://www.geosci-model-dev-discuss.net/gmd-2016-66/
  Haarsma et al 2016]. It is one of the MIP projects for WCRP''s CMIP6 CMIP6 HighResMIP.'
layout: base_hrcm
order: 1
permalink: /research/cmip6-highresmip/highresmip-protocol/
title: HighResMIP protocol
---

<h2>HighResMIP protocol</h2>
<p>The HighResMIP protocol is described in detail in [http://www.geosci-model-dev-discuss.net/gmd-2016-66/ Haarsma et al 2016]. It is one of the MIP projects for WCRP's CMIP6 <a href="https://www.wcrp-climate.org/modelling-wgcm-mip-catalogue/modelling-wgcm-cmip6-endorsed-mips/index.php?t&amp;amp;view=article&amp;amp;id=1068">CMIP6 HighResMIP</a>.</p>
<p></p>
<p>The HighResMIP output requirements are described in the <a href="https://earthsystemcog.org/projects/wip/CMIP6DataRequest%20CMIP6">Data Request</a></p>
<p><br>Below is a short outline of the protocol<br><br></p>
<h4>Tier 1: Forced-atmosphere  runs 1950-2014</h4>
<p>Experiment name: highresSST-present<br><br>Using HadISST2.2.0.0 1/4 degree SST and sea-ice forcing dataset - see <a href="https://hrcm.ceda.ac.uk/research/cmip6-highresmip/highresmip-protocol/sst-and-sea-ice-forcing/">https://hrcm.ceda.ac.uk/research/cmip6-highresmip/highresmip-protocol/sst-and-sea-ice-forcing/ </a></p>
<h4>Tier 2: Coupled runs 1950-2050</h4>
<p>Control:   100 years with 1950's forcing         Experiment name: control-1950</p>
<p>Historic:  1950-2014  with historic forcing     Experiment name: hist-1950</p>
<p>Future:    2015-2050                                      Experiment name: highres-future</p>
<p>Spin-up:  50 year spin-up from EN4 ocean climatology with constant 1950's forcing. Experiment name: spinup-1950</p>
<p></p>
<h4>Tier 3: Forced-atmosphere 2015-2050 (2100)</h4>
<p>2015-2050 (2100)  Experiment name: highresSST-future</p>
<p></p>
<p><img height="450" src="/hrcm/static/media/uploads/HighResMIP_images/highresmip_simulation_diagram_2019.png" width="800"></p>
<p></p>
<p>Motivation of these three Tiers</p>
<p></p>
<p>Focus of HighResMIP is on the 1950-2050 period (Tier 2). This period includes significant past changes and the time horizon for the future is relevant for decision makers.</p>
<p></p>
<p>The division of the forced-atmosphere (AMIP-style) runs in Tier 1 and Tier 3 is to enable NWP centers to participate. It also includes the possibility for end of the century simulations.</p>
<p></p>
<p>Resolution: Atmosphere 20-50 km; Ocean ~0.25 degree</p>
<p></p>
<p>Experiments are repeated with standard resolution. This version is also the entry for DECK runs.</p>
<p></p>
<p>HighResMIP philosophy: No or minimal additional tuning for high resolution version. If tuning is necessary it should be well documented.</p>
<p></p>
<p>Further targeted experiments</p>
<p>Leaf area index (LAI) experiment highresSST-LAI<br><br></p>
<p>Smoothed SST highresSST-smoothed</p>
<p>CFMIP style experiments highresSST-p4K; highresSST-4co2</p>
<p>Abrupt 4XCO2 highres-4co2</p>
