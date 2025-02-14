# CHANGELOG


## v0.4.0 (2025-01-28)

### Bug Fixes

- Fix release titles in Changelog
  ([`d4e08ee`](https://github.com/yambottle/element-array-ephys/commit/d4e08ee2612920d3b183b3de6488c7b94a59de4d))

- Update changelog and semantic release
  ([`77d001d`](https://github.com/yambottle/element-array-ephys/commit/77d001dc2d5e29f9f962857cbbab384cb23303cd))


## v0.3.8 (2025-01-16)


## v0.3.7 (2024-11-01)


## v0.3.6 (2024-09-26)

### Bug Fixes

- **spike_sorting**: Create empty `sorting_analyzer` folder when no units found
  ([`b1104ce`](https://github.com/yambottle/element-array-ephys/commit/b1104ce09158c09175af94682e6e7a0281a7cda2))

- **spikeglx**: Minor bugfix in reading probe model
  ([`2d57102`](https://github.com/yambottle/element-array-ephys/commit/2d57102880d872cf1a4ec037eee5892a87536ff2))

### Features

- **spike_sorting**: Handle cases when no units/spikes are found
  ([`463ec52`](https://github.com/yambottle/element-array-ephys/commit/463ec527ff216a1078ea97665d365d08d140c621))

- **spike_sorting**: Update downstream ephys tables ingestion when NO UNITs found
  ([`451571d`](https://github.com/yambottle/element-array-ephys/commit/451571de595114e59f732c2e1e66298a26d6eeeb))


## v0.3.5 (2024-08-19)

### Bug Fixes

- :bug: fix get_logger missing error
  ([`4802511`](https://github.com/yambottle/element-array-ephys/commit/48025112da9acaab8b6e043b8da56e54a9e9725d))

- :bug: fix input/output data directory
  ([`f6e3e46`](https://github.com/yambottle/element-array-ephys/commit/f6e3e4624255b9b42e89de3e520c8696bc60089f))

- :bug: fix path & typo
  ([`653e7e8`](https://github.com/yambottle/element-array-ephys/commit/653e7e84bcacd3cf7ae382e5236b732db500ad06))

- `spikes` object no longer available from `ComputeSpikeLocations`
  (https://github.com/SpikeInterface/spikeinterface/pull/3015)
  ([`1f05998`](https://github.com/yambottle/element-array-ephys/commit/1f05998e25d848b6aeb73231fa90e616580cd1d8))

- Bugfix inserting `ElectrodeConfig`
  ([`d86928b`](https://github.com/yambottle/element-array-ephys/commit/d86928bf41a2bb0e30c7136d74fc485c9de2b90f))

- Bugfix spikeinterface extractor name
  ([`097d9bb`](https://github.com/yambottle/element-array-ephys/commit/097d9bbf7694e40a839b4cebb49890d1acd325f1))

- Calling `_run_sorter()`
  ([`6155f13`](https://github.com/yambottle/element-array-ephys/commit/6155f13fd755ac76ec79fdd1594b0e96ef8d550b))

- Export default to `False`
  ([`a4a8380`](https://github.com/yambottle/element-array-ephys/commit/a4a8380405673bf2c85861223afa0c9e5e481296))

- Merge fix & formatting
  ([`e8f445c`](https://github.com/yambottle/element-array-ephys/commit/e8f445c3b4b532b3159638e71d231e2048939a90))

- Minor bug in spikes ingestion
  ([`76dfc94`](https://github.com/yambottle/element-array-ephys/commit/76dfc94568bf28296da18905d0b187588bc99397))

- Minor bugfix
  ([`e8870b9`](https://github.com/yambottle/element-array-ephys/commit/e8870b94cf6dc09b251e268c4102fb4b82149da2))

- Recording_extractor_full_dict is deprecated
  (https://github.com/SpikeInterface/spikeinterface/pull/3153)
  ([`c87e493`](https://github.com/yambottle/element-array-ephys/commit/c87e49332f90386acc8eb696e65f87bfd7b6ae24))

- Remove `job_kwargs` for sparsity calculation - memory error in linux container
  ([`4e645eb`](https://github.com/yambottle/element-array-ephys/commit/4e645ebd9b83f5e607e1d18188c0c3ce5f84eb4a))

- Update channel-electrode mapping
  ([`d778b1e`](https://github.com/yambottle/element-array-ephys/commit/d778b1e7d8822173ad43d60707fbb8fa8c7ff801))

- Update ingestion from spikeinterface results
  ([`05ccfdb`](https://github.com/yambottle/element-array-ephys/commit/05ccfdb80cee7418e58322ebb3bbb9f4a1df6b8e))

- Use relative path for phy output
  ([`1ff92dd`](https://github.com/yambottle/element-array-ephys/commit/1ff92dd15db6ff9e8458f53ec96fdffb6b93305d))

- Use tempfile.TemporaryDirectory
  ([`4971108`](https://github.com/yambottle/element-array-ephys/commit/497110816058ae0655cac8f9414b4622905f78a6))

- **probe**: Better handling of different Neuropixels probe types
  ([`aaec763`](https://github.com/yambottle/element-array-ephys/commit/aaec76339954b17a2dbef8aeaa84e92e64bdad35))

- **spikeglx**: Bugfix loading spikeglx data
  ([`d44dbaa`](https://github.com/yambottle/element-array-ephys/commit/d44dbaa03aa8debb2f9d15fe60811a4fcb52a535))

- **spikeglx**: Minor bugfix
  ([`6764f8c`](https://github.com/yambottle/element-array-ephys/commit/6764f8c1adb9a80569f75233028e551cf58d8917))

### Documentation

- :memo: update comments in ephys_no_curation
  ([`673faed`](https://github.com/yambottle/element-array-ephys/commit/673faedc1c8232098888340bab687896cd89e7f1))

### Features

- :ambulance: make all secondary attributes nullable in QualityMetrics
  ([`01ff816`](https://github.com/yambottle/element-array-ephys/commit/01ff816fd4e2077c3b9c3ff4c5c439faddbb43c9))

some sorters don't output values expected by the table

- :art: si_clustering.PreProcessing
  ([`1fceb90`](https://github.com/yambottle/element-array-ephys/commit/1fceb90a1816613a0e86f2f7288ba56ba254de40))

- :art: si_clustering.SIClustering
  ([`df8ed74`](https://github.com/yambottle/element-array-ephys/commit/df8ed7464ebc3452148c0daa1f1e43987d7035ec))

- :sparkles: add EphysRecording.Channel part table
  ([`4b6fc0e`](https://github.com/yambottle/element-array-ephys/commit/4b6fc0e9fe45f2a6b44be466f0731faad301734c))

- :sparkles: add memoized_result implementation in SIClustering
  ([`1faa8f2`](https://github.com/yambottle/element-array-ephys/commit/1faa8f2e0e7f78f1097a220e4282ea4f8d6e7d1b))

- :sparkles: add n.a. to ClusterQualityLabel
  ([`6daf0c5`](https://github.com/yambottle/element-array-ephys/commit/6daf0c5a1f3f40d3700ce09bfa047326b4477cab))

- :sparkles: add PostProcessing table & clean up
  ([`2ed337b`](https://github.com/yambottle/element-array-ephys/commit/2ed337bf0fa8245a7f8d481dc779b072cfcbadd0))

- :sparkles: add quality label mapping
  ([`0898ce5`](https://github.com/yambottle/element-array-ephys/commit/0898ce5cdaeb7656ed7142f395351dfcde652d40))

- :sparkles: improve to_probeinterface
  ([`6bee166`](https://github.com/yambottle/element-array-ephys/commit/6bee166f5fe356ddea10e1a5b391e6daf6929ec9))

- :sparkles: Ingest EphysRecording.Channel
  ([`727af24`](https://github.com/yambottle/element-array-ephys/commit/727af24cca6f00fc35651f88f7f258d2ab67e43e))

- :sparkles: modify CuratedClustering make function for spike interface
  ([`e8d9854`](https://github.com/yambottle/element-array-ephys/commit/e8d9854f4014302248d483604faaa2b4f2858fc2))

- :sparkles: modify QualityMetrics make function
  ([`90d1ba4`](https://github.com/yambottle/element-array-ephys/commit/90d1ba4e4c87493c4e79ae93ed139ee0f5e3218f))

- :sparkles: replace get_neuropixels_channel2electrode_map with channel_info
  ([`f70ae4e`](https://github.com/yambottle/element-array-ephys/commit/f70ae4ee1e294b0ba1173fa6a9b1255e2d27f6b3))

- :sparkles: Update WaveformSet make function
  ([`226142b`](https://github.com/yambottle/element-array-ephys/commit/226142b82614f4964a3f7c8655ffd2ca6f43dd3d))

- Add `memoized_result` on spike sorting
  ([`51e2ced`](https://github.com/yambottle/element-array-ephys/commit/51e2ced3f36fa1b69bacf69ea1fbf295c84eaf16))

- In data ingestion, set peak_sign="both"
  ([`b459709`](https://github.com/yambottle/element-array-ephys/commit/b45970974df001319a4ebae182bf291313f5e39a))

- Prototyping with the new `sorting_analyzer`
  ([`c934e67`](https://github.com/yambottle/element-array-ephys/commit/c934e67ea6e5de2e30b35dbc10ab547e49917159))

- Replace `output_folder` with `folder` when calling `run_sorter`, use default value for `peak_sign`
  ([`1a1b18f`](https://github.com/yambottle/element-array-ephys/commit/1a1b18f8a52b83298bffc8d82555ccc147151dd1))

- Save spike interface results with relative path
  ([`67a1ffc`](https://github.com/yambottle/element-array-ephys/commit/67a1ffc767261e5a9c7d9e7c85d418005c3dac80))

- Separate `export` (phy and report) into a separate table
  ([`38fdfb2`](https://github.com/yambottle/element-array-ephys/commit/38fdfb2a5fd44f1115aa4f1660482e1639eaa3c2))

- Test spikeinterface for spikeglx data
  ([`015341c`](https://github.com/yambottle/element-array-ephys/commit/015341c1127300e10e9011ec5d49a96abc3322f0))

- Update ingestion to be compatible with spikeinterface 0.101+
  ([`3666cda`](https://github.com/yambottle/element-array-ephys/commit/3666cda077448cc40d7b7e9c219c9c489396cbd6))

- **spikesorting**: Save to phy and generate report
  ([`f8ffd77`](https://github.com/yambottle/element-array-ephys/commit/f8ffd7760cb1be6ac19d24e37ebf69d11d773972))

### Refactoring

- :art: clean up spikeinterface import & remove unused import
  ([`849b576`](https://github.com/yambottle/element-array-ephys/commit/849b576c8982b9231b4b1167740d2d1a2ad1cbdd))

- :art: refactor PostProcessing
  ([`d47be56`](https://github.com/yambottle/element-array-ephys/commit/d47be56dd8baeb88d8238701c1aa5ada457d3c36))

- :fire: remove & get_neuropixels_channel2electrode_map and generate_electrode_config
  ([`ea39839`](https://github.com/yambottle/element-array-ephys/commit/ea398391223d6ce8ac26ea22efc2240c86a95525))

- :recycle: change sorter_name
  ([`88ce139`](https://github.com/yambottle/element-array-ephys/commit/88ce139bec18a0a01b13943b92c57dbcbc64e074))

- :recycle: clean up import & docstring
  ([`6e20a11`](https://github.com/yambottle/element-array-ephys/commit/6e20a11e92455220eebc065cd4870dc856739544))

- :recycle: Fix metrics directory in QualityMetrics
  ([`417219f`](https://github.com/yambottle/element-array-ephys/commit/417219fd4baeeadc1d9e4feeaa29ef04c4b21555))

- :recycle: import si module & re-organize imports
  ([`00b82f8`](https://github.com/yambottle/element-array-ephys/commit/00b82f81017fdb92459cd334cda8bb3dc49b0fde))

- :recycle: improve if else block in EphysRecording
  ([`8ab4c58`](https://github.com/yambottle/element-array-ephys/commit/8ab4c58a9d5c744bc3c071f31f360873ff8ee8a2))

- :recycle: update the output dir for CuratedClustering
  ([`bab86b7`](https://github.com/yambottle/element-array-ephys/commit/bab86b7c1471f02e2c9d95c1f4ee8442345b3817))

- Fix typo & black formatting
  ([`be5135e`](https://github.com/yambottle/element-array-ephys/commit/be5135e05ba40bb2054a18e9b00486ea1ba411d0))


## v0.3.4 (2024-03-22)


## v0.3.3 (2024-01-24)


## v0.3.2 (2024-01-12)

### Bug Fixes

- **probe_geometry**: Bugfix in x_coords for probe with staggered electrode positions
  ([`54d4fac`](https://github.com/yambottle/element-array-ephys/commit/54d4facd38a79ba9b6e40c01174fdb04e6dee43d))


## v0.3.1 (2024-01-04)


## v0.3.0 (2023-11-09)


## v0.2.11 (2023-06-30)


## v0.2.10 (2023-05-26)


## v0.2.9 (2023-05-11)


## v0.2.8 (2023-04-28)


## v0.2.7 (2023-04-19)


## v0.2.6 (2023-04-18)


## v0.2.5 (2023-04-13)


## v0.2.4 (2023-03-10)


## v0.2.3 (2023-02-14)

### Bug Fixes

- :bug: import from __future__ module
  ([`4d9ab28`](https://github.com/yambottle/element-array-ephys/commit/4d9ab28609b161be986cda2872778d7a403277f3))

this supports backward compability with typing


## v0.2.2 (2023-01-11)


## v0.2.1 (2023-01-09)

### Documentation

- :memo: add | update docstrings
  ([`4999d64`](https://github.com/yambottle/element-array-ephys/commit/4999d64980e4cf278f872159c7d327387939ee12))

- :memo: name change & add docstring
  ([`d9c75c8`](https://github.com/yambottle/element-array-ephys/commit/d9c75c8ea425eb38dc8e714639ad341edf39cafd))

### Refactoring

- :pencil2: fix typos
  ([`efca82e`](https://github.com/yambottle/element-array-ephys/commit/efca82e352adee21c6979e94078c1c82b8b423aa))

- **deps**: :heavy_minus_sign: remove ibllib deps and add acorr func
  ([`c613164`](https://github.com/yambottle/element-array-ephys/commit/c613164ae90cac220c1726a9eb2e12f336f876db))


## v0.2.0 (2022-11-03)

### Bug Fixes

- :bug: use to_plotly_json() instead of to_json()
  ([`69b2796`](https://github.com/yambottle/element-array-ephys/commit/69b2796285690bcb68d2e3185608a6e33172c0ea))

### Features

- :sparkles: add a report schema and plotting png figures
  ([`66743cc`](https://github.com/yambottle/element-array-ephys/commit/66743cc3dcdc22a35ddd24f7c694278c2903957a))

- :sparkles: Merge branch 'plotly' into no_curation_plot
  ([`06c1064`](https://github.com/yambottle/element-array-ephys/commit/06c1064dd890d68afc90a9cc3aca3961edab2691))


## v0.1.4 (2022-07-11)


## v0.1.3 (2022-06-16)


## v0.1.2 (2022-06-09)


## v0.1.1 (2022-06-01)
