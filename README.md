# shairport-sync Ansible Role

The unofficial ansible role for installing and configuring [mikebrady's](https://github.com/mikebrady) [shairport-sync](https://github.com/mikebrady/shairport-sync).

Instructions from <https://github.com/mikebrady/shairport-sync/blob/development/BUILDFORAP2.md>


## Requirements

This role is only compatible with those devices outlined in the [shairport-sync project](https://github.com/mikebrady/shairport-sync). This is currently limited to newer version of the popular Linux distributions. This has currently only been tested on Debian.

## Role Variables

For more details on these configuration variables see <https:#github.com/mikebrady/shairport-sync/blob/development/scripts/shairport-sync.conf>

| Variable Name | Default |
| -- | -- |
| airplay_version | `2` |
| alsa_buffer_size | `null` |
| alsa_disable_standby_mode | `null` |
| alsa_disable_standby_mode_silence_scan_interval | `null` |
| alsa_disable_standby_mode_silence_threshold | `null` |
| alsa_disable_synchronization | `null` |
| alsa_maximum_stall_time | `null` |
| alsa_mixer_control_name | `null` |
| alsa_mixer_device | `null` |
| alsa_output_device | `"hw:0"` |
| alsa_output_format | `null` |
| alsa_output_rate | `null` |
| alsa_period_size | `null` |
| alsa_use_hardware_mute_if_available | `null` |
| alsa_use_mmap_if_available | `null` |
| alsa_use_precision_timing | `null` |
| configuration_file_path | `"./shairport-sync.conf"` |
| diagnostics_disable_resend_requests | `null` |
| diagnostics_drop_this_fraction_of_audio_packets | `null` |
| diagnostics_log_output_to | `null` |
| diagnostics_log_show_file_and_line | `null` |
| diagnostics_log_show_time_since_last_message | `null` |
| diagnostics_log_show_time_since_startup | `null` |
| diagnostics_log_verbosity | `null` |
| diagnostics_retain_cover_art | `null` |
| diagnostics_statistics | `null` |
| dsp_convolution | `null` |
| dsp_convolution_gain | `null` |
| dsp_convolution_ir_file | `null` |
| dsp_convolution_max_length | `null` |
| dsp_loudness | `null` |
| dsp_loudness_reference_volume_db | `null` |
| general_alac_decoder | `null` |
| general_audio_backend_buffer_desired_length_in_seconds | `null` |
| general_audio_backend_buffer_interpolation_threshold_in_seconds | `null` |
| general_audio_backend_latency_offset_in_seconds | `null` |
| general_audio_backend_silent_lead_in_time | `null` |
| general_dbus_service_bus | `null` |
| general_drift_tolerance_in_seconds | `null` |
| general_ignore_volume_control | `null` |
| general_interface | `null` |
| general_interpolation | `null` |
| general_mdns_backend | `null` |
| general_missing_port_dacp_scan_interval_seconds | `null` |
| general_mpris_service_bus | `null` |
| general_name | `null` |
| general_output_backend | `null` |
| general_password | `null` |
| general_playback_mode | `null` |
| general_port | `null` |
| general_regtype | `null` |
| general_resend_control_check_interval_time | `null` |
| general_resend_control_first_check_time | `null` |
| general_resend_control_last_check_time | `null` |
| general_resync_threshold_in_seconds | `null` |
| general_run_this_before_play_begins | `null` |
| general_run_this_when_volume_is_set | `null` |
| general_udp_port_base | `null` |
| general_udp_port_range | `null` |
| general_volume_control_profile | `null` |
| general_volume_max_db | `null` |
| general_volume_range_combined_hardware_priority | `null` |
| general_volume_range_db | `null` |
| metadata_cover_art_cache_directory | `null` |
| metadata_enabled | `null` |
| metadata_include_cover_art | `null` |
| metadata_pipe_name | `null` |
| metadata_pipe_timeout | `null` |
| metadata_socket_address | `null` |
| metadata_socket_msglength | `null` |
| metadata_socket_port | `null` |
| mqtt_cafile | `null` |
| mqtt_capath | `null` |
| mqtt_certfile | `null` |
| mqtt_enable_remote | `null` |
| mqtt_enabled | `null` |
| mqtt_hostname | `null` |
| mqtt_keyfile | `null` |
| mqtt_password | `null` |
| mqtt_port | `null` |
| mqtt_publish_cover | `null` |
| mqtt_publish_parsed | `null` |
| mqtt_publish_raw | `null` |
| mqtt_topic | `null` |
| mqtt_username | `null` |
| pa_application_name | `null` |
| pa_autoconnect_pattern | `null` |
| pa_bufsz | `null` |
| pa_client_name | `null` |
| pa_server | `null` |
| pa_sink | `null` |
| pa_soxr_resample_quality | `null` |
| pipe_name | `null` |
| sessioncontrol_active_state_timeout | `null` |
| sessioncontrol_allow_session_interruption | `null` |
| sessioncontrol_run_this_after_exiting_active_state | `null` |
| sessioncontrol_run_this_after_play_ends | `null` |
| sessioncontrol_run_this_before_entering_active_state | `null` |
| sessioncontrol_run_this_before_play_begins | `null` |
| sessioncontrol_run_this_if_an_unfixable_error_is_detected | `null` |
| sessioncontrol_session_timeout | `null` |
| sessioncontrol_wait_for_completion | `null` |
| sndio_bufsz | `null` |
| sndio_device | `null` |
| sndio_format | `null` |
| sndio_rate | `null` |
| sndio_round | `null` |
| version | `"4.0-dev` |


## Dependencies

N/A

## Example Playbook

```yaml
roles:
    - role: ansible-role-shairport-sync

```

## License

MIT
