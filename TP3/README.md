# TP3: Sonorisation de l'animation 
<?xml version='1.0' encoding='utf-8'?>
<mlt LC_NUMERIC="en_US.UTF-8" producer="main_bin" root="C:/Users/2397681/Videos" version="7.43.0">
 <profile colorspace="709" description="HD 720p 25 fps" display_aspect_den="9" display_aspect_num="16" frame_rate_den="1" frame_rate_num="25" height="720" progressive="1" sample_aspect_den="1" sample_aspect_num="1" width="1280"/>
 <producer id="producer0" in="00:00:00.000" out="00:05:08.280">
  <property name="length">2147483647</property>
  <property name="eof">continue</property>
  <property name="resource">black</property>
  <property name="aspect_ratio">1</property>
  <property name="mlt_service">color</property>
  <property name="kdenlive:playlistid">black_track</property>
  <property name="mlt_image_format">rgba</property>
  <property name="set.test_audio">0</property>
 </producer>
 <playlist id="playlist0"/>
 <chain id="chain0" out="00:02:04.160">
  <property name="length">3105</property>
  <property name="eof">pause</property>
  <property name="resource">C:/Users/2397681/Downloads/618895__sizeffects__home-alarm-keypad-beeps-close-perspective.wav</property>
  <property name="mlt_service">avformat-novalidate</property>
  <property name="seekable">1</property>
  <property name="audio_index">0</property>
  <property name="video_index">-1</property>
  <property name="astream">0</property>
  <property name="kdenlive:folderid">-1</property>
  <property name="kdenlive:id">10</property>
  <property name="kdenlive:control_uuid">{aabceff7-9096-4de6-8664-564f10d1a1fc}</property>
  <property name="kdenlive:clip_type">1</property>
  <property name="kdenlive:file_size">17918768</property>
  <property name="kdenlive:file_hash">30f496561bda254206474104f7b7c678</property>
  <property name="kdenlive:record_start_frame">504000</property>
  <property name="kdenlive:kextractor">1</property>
  <property name="kdenlive:meta.extractor.Bitrate:">1152 kb/s</property>
  <property name="meta.media.nb_streams">1</property>
  <property name="meta.media.0.stream.type">audio</property>
  <property name="meta.media.0.codec.sample_fmt">s32</property>
  <property name="meta.media.0.codec.sample_rate">48000</property>
  <property name="meta.media.0.codec.channels">1</property>
  <property name="meta.media.0.codec.layout">mono</property>
  <property name="meta.media.0.codec.name">pcm_s24le</property>
  <property name="meta.media.0.codec.long_name">PCM signed 24-bit little-endian</property>
  <property name="meta.media.0.codec.bit_rate">1152000</property>
  <property name="meta.attr.comment.markup">zSPEED=25.000ND&#xd;
zTAKE=003&#xd;
zUBITS=00000000&#xd;
zSCENE=&#xd;
zTAPE=&#xd;
zCIRCLED=FALSE&#xd;
zTRK4=Tr2&#xd;
zNOTE=&#xd;
</property>
  <property name="meta.attr.encoded_by.markup">ZOOM F6</property>
  <property name="meta.attr.date.markup">2021-11-22</property>
  <property name="meta.attr.creation_time.markup">09:51:50</property>
  <property name="meta.attr.time_reference.markup">24192000</property>
  <property name="meta.attr.coding_history.markup">BaseHead Edited</property>
  <property name="xml">was here</property>
  <property name="mute_on_pause">0</property>
  <property name="set.test_audio">1</property>
  <property name="set.test_image">1</property>
 </chain>
 <playlist id="playlist1">
  <blank length="00:00:10.400"/>
  <entry in="00:00:01.680" out="00:00:03.000" producer="chain0">
   <property name="kdenlive:audio_index">0</property>
   <property name="kdenlive:id">10</property>
  </entry>
 </playlist>
 <tractor id="tractor0" in="00:00:00.000" out="00:00:11.720">
  <property name="kdenlive:audio_track">1</property>
  <property name="kdenlive:trackheight">84</property>
  <property name="kdenlive:timeline_active">1</property>
  <track hide="both" producer="playlist0"/>
  <track hide="both" producer="playlist1"/>
  <filter id="filter0">
   <property name="window">75</property>
   <property name="max_gain">20dB</property>
   <property name="channel_mask">-1</property>
   <property name="mlt_service">volume</property>
   <property name="internal_added">237</property>
   <property name="disable">1</property>
  </filter>
  <filter id="filter1">
   <property name="channel">-1</property>
   <property name="mlt_service">panner</property>
   <property name="internal_added">237</property>
   <property name="start">0.5</property>
   <property name="disable">1</property>
  </filter>
  <filter id="filter2">
   <property name="iec_scale">0</property>
   <property name="prefix">meta.media.audio_level.</property>
   <property name="mlt_service">audiolevel</property>
   <property name="internal_added">237</property>
   <property name="dbpeak">1</property>
   <property name="disable">1</property>
  </filter>
 </tractor>
 <chain id="chain1" out="00:00:10.960">
  <property name="length">275</property>
  <property name="eof">pause</property>
  <property name="resource">C:/Users/2397681/Downloads/863082__alexarje__bed-sheets-soundaction-104.wav</property>
  <property name="mlt_service">avformat-novalidate</property>
  <property name="seekable">1</property>
  <property name="audio_index">0</property>
  <property name="video_index">-1</property>
  <property name="astream">0</property>
  <property name="kdenlive:folderid">-1</property>
  <property name="kdenlive:id">20</property>
  <property name="kdenlive:control_uuid">{3ba702ba-8ce0-4010-9653-6119ef5239a5}</property>
  <property name="kdenlive:clip_type">1</property>
  <property name="kdenlive:file_size">1056846</property>
  <property name="kdenlive:file_hash">4373839fd48a56525b948d934712841f</property>
  <property name="kdenlive:record_start_frame">-1</property>
  <property name="meta.media.nb_streams">1</property>
  <property name="meta.media.0.stream.type">audio</property>
  <property name="meta.media.0.codec.sample_fmt">s16</property>
  <property name="meta.media.0.codec.sample_rate">48000</property>
  <property name="meta.media.0.codec.channels">1</property>
  <property name="meta.media.0.codec.layout">mono</property>
  <property name="meta.media.0.codec.name">pcm_s16le</property>
  <property name="meta.media.0.codec.long_name">PCM signed 16-bit little-endian</property>
  <property name="meta.media.0.codec.bit_rate">768000</property>
  <property name="meta.attr.encoder.markup">Lavf58.76.100</property>
  <property name="xml">was here</property>
  <property name="mute_on_pause">0</property>
  <property name="set.test_audio">0</property>
  <property name="set.test_image">1</property>
 </chain>
 <playlist id="playlist2">
  <blank length="00:00:16.440"/>
  <entry in="00:00:04.120" out="00:00:05.920" producer="chain1">
   <property name="kdenlive:id">20</property>
  </entry>
  <entry in="00:00:07.600" out="00:00:09.840" producer="chain1">
   <property name="kdenlive:id">20</property>
  </entry>
 </playlist>
 <playlist id="playlist3"/>
 <tractor id="tractor1" in="00:00:00.000" out="00:00:20.520">
  <property name="kdenlive:audio_track">1</property>
  <property name="kdenlive:trackheight">84</property>
  <property name="kdenlive:timeline_active">1</property>
  <track hide="video" producer="playlist2"/>
  <track hide="video" producer="playlist3"/>
  <filter id="filter3">
   <property name="window">75</property>
   <property name="max_gain">20dB</property>
   <property name="channel_mask">-1</property>
   <property name="mlt_service">volume</property>
   <property name="internal_added">237</property>
   <property name="disable">1</property>
  </filter>
  <filter id="filter4">
   <property name="channel">-1</property>
   <property name="mlt_service">panner</property>
   <property name="internal_added">237</property>
   <property name="start">0.5</property>
   <property name="disable">1</property>
  </filter>
  <filter id="filter5">
   <property name="iec_scale">0</property>
   <property name="prefix">meta.media.audio_level.</property>
   <property name="mlt_service">audiolevel</property>
   <property name="internal_added">237</property>
   <property name="dbpeak">1</property>
   <property name="disable">1</property>
  </filter>
 </tractor>
 <chain id="chain2" out="00:04:15.120">
  <property name="length">6379</property>
  <property name="eof">pause</property>
  <property name="resource">C:/Users/2397681/Downloads/555053__brunoauzet__playground.wav</property>
  <property name="mlt_service">avformat-novalidate</property>
  <property name="seekable">1</property>
  <property name="audio_index">0</property>
  <property name="video_index">-1</property>
  <property name="astream">0</property>
  <property name="kdenlive:folderid">-1</property>
  <property name="kdenlive:id">14</property>
  <property name="kdenlive:control_uuid">{935b4c12-b980-4689-a5a0-590503b9c74d}</property>
  <property name="kdenlive:clip_type">1</property>
  <property name="kdenlive:file_size">76175124</property>
  <property name="kdenlive:file_hash">ce207183c3e45d93b60e559a329c5ba2</property>
  <property name="kdenlive:record_start_frame">10354308</property>
  <property name="meta.media.nb_streams">1</property>
  <property name="meta.media.0.stream.type">audio</property>
  <property name="meta.media.0.codec.sample_fmt">s32</property>
  <property name="meta.media.0.codec.sample_rate">48000</property>
  <property name="meta.media.0.codec.channels">2</property>
  <property name="meta.media.0.codec.layout">independent</property>
  <property name="meta.media.0.codec.name">pcm_s24le</property>
  <property name="meta.media.0.codec.long_name">PCM signed 24-bit little-endian</property>
  <property name="meta.media.0.codec.bit_rate">2304000</property>
  <property name="meta.attr.encoded_by.markup">Pro Tools</property>
  <property name="meta.attr.originator_reference.markup">c40N3cqcU6jaaaGk</property>
  <property name="meta.attr.date.markup">2021-01-22</property>
  <property name="meta.attr.creation_time.markup">09:53:23</property>
  <property name="meta.attr.time_reference.markup">497006786</property>
  <property name="xml">was here</property>
  <property name="mute_on_pause">0</property>
  <property name="set.test_audio">0</property>
  <property name="set.test_image">1</property>
 </chain>
 <chain id="chain3" out="00:01:43.040">
  <property name="length">2577</property>
  <property name="eof">pause</property>
  <property name="resource">C:/Users/2397681/Downloads/405224__soundsexciting__kids-fighting.wav</property>
  <property name="mlt_service">avformat-novalidate</property>
  <property name="seekable">1</property>
  <property name="audio_index">0</property>
  <property name="video_index">-1</property>
  <property name="astream">0</property>
  <property name="kdenlive:folderid">-1</property>
  <property name="kdenlive:id">17</property>
  <property name="kdenlive:control_uuid">{8ca42706-a55c-4984-bed3-5b43a8e3d6b8}</property>
  <property name="kdenlive:clip_type">1</property>
  <property name="kdenlive:file_size">36372644</property>
  <property name="kdenlive:file_hash">267e038c3ca2a75434974a16657fbdda</property>
  <property name="kdenlive:record_start_frame">-1</property>
  <property name="meta.media.nb_streams">1</property>
  <property name="meta.media.0.stream.type">audio</property>
  <property name="meta.media.0.codec.sample_fmt">flt</property>
  <property name="meta.media.0.codec.sample_rate">44100</property>
  <property name="meta.media.0.codec.channels">2</property>
  <property name="meta.media.0.codec.layout">independent</property>
  <property name="meta.media.0.codec.name">pcm_f32le</property>
  <property name="meta.media.0.codec.long_name">PCM 32-bit floating point little-endian</property>
  <property name="meta.media.0.codec.bit_rate">2822400</property>
  <property name="meta.attr.title.markup">Kids fighting</property>
  <property name="xml">was here</property>
  <property name="mute_on_pause">0</property>
  <property name="set.test_audio">0</property>
  <property name="set.test_image">1</property>
 </chain>
 <chain id="chain4" out="00:00:19.360">
  <property name="length">485</property>
  <property name="eof">pause</property>
  <property name="resource">C:/Users/2397681/Downloads/624477__valentinpetiteau__cloth-rustle-heavy-snap-clothespin.wav</property>
  <property name="mlt_service">avformat-novalidate</property>
  <property name="seekable">1</property>
  <property name="audio_index">0</property>
  <property name="video_index">-1</property>
  <property name="astream">0</property>
  <property name="kdenlive:folderid">-1</property>
  <property name="kdenlive:id">18</property>
  <property name="kdenlive:control_uuid">{29fc1c5b-c778-4981-961a-e7225864bc6d}</property>
  <property name="kdenlive:clip_type">1</property>
  <property name="kdenlive:file_size">5619128</property>
  <property name="kdenlive:file_hash">fbd82c8b28d347492082c96dd668d837</property>
  <property name="kdenlive:record_start_frame">44362265</property>
  <property name="meta.media.nb_streams">1</property>
  <property name="meta.media.0.stream.type">audio</property>
  <property name="meta.media.0.codec.sample_fmt">s32</property>
  <property name="meta.media.0.codec.sample_rate">96000</property>
  <property name="meta.media.0.codec.channels">1</property>
  <property name="meta.media.0.codec.layout">mono</property>
  <property name="meta.media.0.codec.name">pcm_s24le</property>
  <property name="meta.media.0.codec.long_name">PCM signed 24-bit little-endian</property>
  <property name="meta.media.0.codec.bit_rate">2304000</property>
  <property name="meta.attr.encoded_by.markup">iZotope RX 9 Advanced Audio Edi</property>
  <property name="meta.attr.originator_reference.markup">USIZT003358201786123811069178984</property>
  <property name="meta.attr.date.markup">2022-02-21</property>
  <property name="meta.attr.creation_time.markup">12:38:11</property>
  <property name="meta.attr.time_reference.markup">4258777457</property>
  <property name="meta.attr.coding_history.markup">A=PCM,F=96000,W=24,M=stereo,T=ZOOM Handy Recorder H5 XY5 STEREO            </property>
  <property name="xml">was here</property>
  <property name="mute_on_pause">0</property>
  <property name="set.test_audio">0</property>
  <property name="set.test_image">1</property>
 </chain>
 <chain id="chain5" out="00:01:02.600">
  <property name="length">1566</property>
  <property name="eof">pause</property>
  <property name="resource">C:/Users/2397681/Downloads/815791__lydgutten__strange-heartbeats.m4a</property>
  <property name="mlt_service">avformat-novalidate</property>
  <property name="seekable">1</property>
  <property name="audio_index">0</property>
  <property name="video_index">-1</property>
  <property name="astream">0</property>
  <property name="kdenlive:folderid">-1</property>
  <property name="kdenlive:id">19</property>
  <property name="kdenlive:control_uuid">{a51a7a32-d809-42e4-a504-a7b2527f745c}</property>
  <property name="kdenlive:clip_type">1</property>
  <property name="kdenlive:file_size">2056367</property>
  <property name="kdenlive:file_hash">e71893e3ab495fe957fd8bfe8a8eb0a7</property>
  <property name="kdenlive:record_start_frame">-1</property>
  <property name="meta.media.nb_streams">1</property>
  <property name="meta.media.0.stream.type">audio</property>
  <property name="meta.media.0.codec.sample_fmt">fltp</property>
  <property name="meta.media.0.codec.sample_rate">48000</property>
  <property name="meta.media.0.codec.channels">2</property>
  <property name="meta.media.0.codec.layout">stereo</property>
  <property name="meta.media.0.codec.name">aac</property>
  <property name="meta.media.0.codec.long_name">AAC (Advanced Audio Coding)</property>
  <property name="meta.media.0.codec.bit_rate">256019</property>
  <property name="meta.attr.0.stream.creation_time.markup">2025-03-12T16:18:10.000000Z</property>
  <property name="meta.attr.0.stream.language.markup">eng</property>
  <property name="meta.attr.0.stream.handler_name.markup">SoundHandle</property>
  <property name="meta.attr.major_brand.markup">3gp4</property>
  <property name="meta.attr.minor_version.markup">0</property>
  <property name="meta.attr.compatible_brands.markup">isom3gp4</property>
  <property name="meta.attr.creation_time.markup">2025-03-12T16:18:10.000000Z</property>
  <property name="meta.attr.com.android.version.markup">14</property>
  <property name="xml">was here</property>
  <property name="mute_on_pause">0</property>
  <property name="set.test_audio">0</property>
  <property name="set.test_image">1</property>
 </chain>
 <playlist id="playlist4">
  <blank length="00:00:04.920"/>
  <entry in="00:00:01.200" out="00:00:04.200" producer="chain2">
   <property name="kdenlive:id">14</property>
   <property name="kdenlive:activeeffect">0</property>
   <filter id="filter6">
    <property name="window">75</property>
    <property name="max_gain">20dB</property>
    <property name="level">00:00:01.200=-15</property>
    <property name="channel_mask">-1</property>
    <property name="mlt_service">volume</property>
    <property name="kdenlive_id">volume</property>
    <property name="kdenlive:collapsed">0</property>
   </filter>
  </entry>
  <blank length="00:00:03.000"/>
  <entry in="00:00:09.160" out="00:00:12.680" producer="chain3">
   <property name="kdenlive:id">17</property>
  </entry>
  <blank length="00:00:01.000"/>
  <entry in="00:00:00.000" out="00:00:00.280" producer="chain4">
   <property name="kdenlive:id">18</property>
  </entry>
  <blank length="00:00:00.600"/>
  <entry in="00:00:00.600" out="00:00:04.080" producer="chain5">
   <property name="kdenlive:id">19</property>
   <property name="kdenlive:activeeffect">0</property>
  </entry>
 </playlist>
 <playlist id="playlist5"/>
 <tractor id="tractor2" in="00:00:00.000" out="00:00:19.920">
  <property name="kdenlive:audio_track">1</property>
  <property name="kdenlive:trackheight">84</property>
  <property name="kdenlive:timeline_active">1</property>
  <track hide="video" producer="playlist4"/>
  <track hide="video" producer="playlist5"/>
  <filter id="filter7">
   <property name="window">75</property>
   <property name="max_gain">20dB</property>
   <property name="channel_mask">-1</property>
   <property name="mlt_service">volume</property>
   <property name="internal_added">237</property>
   <property name="disable">1</property>
  </filter>
  <filter id="filter8">
   <property name="channel">-1</property>
   <property name="mlt_service">panner</property>
   <property name="internal_added">237</property>
   <property name="start">0.5</property>
   <property name="disable">1</property>
  </filter>
  <filter id="filter9">
   <property name="iec_scale">0</property>
   <property name="prefix">meta.media.audio_level.</property>
   <property name="mlt_service">audiolevel</property>
   <property name="internal_added">237</property>
   <property name="dbpeak">1</property>
   <property name="disable">1</property>
  </filter>
 </tractor>
 <chain id="chain6" out="00:00:27.760">
  <property name="length">695</property>
  <property name="eof">pause</property>
  <property name="resource">C:/Users/2397681/Downloads/837240__petercornell__smoke-exhale-blow-humdrum.wav</property>
  <property name="mlt_service">avformat-novalidate</property>
  <property name="seekable">1</property>
  <property name="audio_index">0</property>
  <property name="video_index">-1</property>
  <property name="astream">0</property>
  <property name="kdenlive:folderid">-1</property>
  <property name="kdenlive:id">13</property>
  <property name="kdenlive:control_uuid">{6f2dbf0b-ef14-4866-94f4-dead868b8096}</property>
  <property name="kdenlive:clip_type">1</property>
  <property name="kdenlive:file_size">4025980</property>
  <property name="kdenlive:file_hash">aea9829f1968fb12d212e5c9dd67406e</property>
  <property name="kdenlive:record_start_frame">2275533</property>
  <property name="meta.media.nb_streams">1</property>
  <property name="meta.media.0.stream.type">audio</property>
  <property name="meta.media.0.codec.sample_fmt">s32</property>
  <property name="meta.media.0.codec.sample_rate">48000</property>
  <property name="meta.media.0.codec.channels">1</property>
  <property name="meta.media.0.codec.layout">mono</property>
  <property name="meta.media.0.codec.name">pcm_s24le</property>
  <property name="meta.media.0.codec.long_name">PCM signed 24-bit little-endian</property>
  <property name="meta.media.0.codec.bit_rate">1152000</property>
  <property name="meta.attr.encoded_by.markup">Pro Tools</property>
  <property name="meta.attr.originator_reference.markup">aa40QdPQSDQk</property>
  <property name="meta.attr.date.markup">2023-06-20</property>
  <property name="meta.attr.creation_time.markup">17:40:01</property>
  <property name="meta.attr.time_reference.markup">109225600</property>
  <property name="meta.attr.umid.markup">0x060A2B340101010501010F1013000000A76CAA90EAD38000D87D48007D779814</property>
  <property name="xml">was here</property>
  <property name="mute_on_pause">0</property>
  <property name="set.test_audio">0</property>
  <property name="set.test_image">1</property>
 </chain>
 <chain id="chain7" out="00:02:02.960">
  <property name="length">3075</property>
  <property name="eof">pause</property>
  <property name="resource">C:/Users/2397681/Downloads/326404__mornedelport__reception-background-chatter-amb.wav</property>
  <property name="mlt_service">avformat-novalidate</property>
  <property name="seekable">1</property>
  <property name="audio_index">0</property>
  <property name="video_index">-1</property>
  <property name="astream">0</property>
  <property name="kdenlive:folderid">-1</property>
  <property name="kdenlive:id">16</property>
  <property name="kdenlive:control_uuid">{bfd0fcc5-e9fd-4941-85e6-3a1c97462af8}</property>
  <property name="kdenlive:clip_type">1</property>
  <property name="kdenlive:file_size">35424736</property>
  <property name="kdenlive:file_hash">f222c6c9eec407fab70e266748e8a88a</property>
  <property name="kdenlive:record_start_frame">-1</property>
  <property name="meta.media.nb_streams">1</property>
  <property name="meta.media.0.stream.type">audio</property>
  <property name="meta.media.0.codec.sample_fmt">s32</property>
  <property name="meta.media.0.codec.sample_rate">48000</property>
  <property name="meta.media.0.codec.channels">2</property>
  <property name="meta.media.0.codec.layout">independent</property>
  <property name="meta.media.0.codec.name">pcm_s24le</property>
  <property name="meta.media.0.codec.long_name">PCM signed 24-bit little-endian</property>
  <property name="meta.media.0.codec.bit_rate">2304000</property>
  <property name="meta.attr.encoded_by.markup">REAPER</property>
  <property name="meta.attr.date.markup">2015-10-27</property>
  <property name="meta.attr.creation_time.markup">12-42-29</property>
  <property name="meta.attr.time_reference.markup">0</property>
  <property name="xml">was here</property>
  <property name="mute_on_pause">0</property>
  <property name="set.test_audio">0</property>
  <property name="set.test_image">1</property>
 </chain>
 <playlist id="playlist6">
  <blank length="00:00:04.920"/>
  <entry in="00:00:05.320" out="00:00:08.480" producer="chain6">
   <property name="kdenlive:id">13</property>
   <property name="kdenlive:activeeffect">0</property>
   <filter id="filter10">
    <property name="window">75</property>
    <property name="max_gain">20dB</property>
    <property name="level">00:00:05.320=9</property>
    <property name="channel_mask">-1</property>
    <property name="mlt_service">volume</property>
    <property name="kdenlive_id">volume</property>
    <property name="kdenlive:collapsed">0</property>
   </filter>
  </entry>
  <entry in="00:00:03.360" out="00:00:06.120" producer="chain7">
   <property name="kdenlive:id">16</property>
  </entry>
  <blank length="00:00:00.040"/>
  <entry in="00:00:05.320" out="00:00:08.480" producer="chain6">
   <property name="kdenlive:id">13</property>
   <filter id="filter11">
    <property name="window">75</property>
    <property name="max_gain">20dB</property>
    <property name="level">00:00:05.320=9</property>
    <property name="channel_mask">-1</property>
    <property name="mlt_service">volume</property>
    <property name="kdenlive_id">volume</property>
    <property name="kdenlive:collapsed">0</property>
   </filter>
  </entry>
 </playlist>
 <playlist id="playlist7"/>
 <tractor id="tractor3" in="00:00:00.000" out="00:00:14.120">
  <property name="kdenlive:audio_track">1</property>
  <property name="kdenlive:trackheight">84</property>
  <property name="kdenlive:timeline_active">1</property>
  <track hide="video" producer="playlist6"/>
  <track hide="video" producer="playlist7"/>
  <filter id="filter12">
   <property name="window">75</property>
   <property name="max_gain">20dB</property>
   <property name="channel_mask">-1</property>
   <property name="mlt_service">volume</property>
   <property name="internal_added">237</property>
   <property name="disable">1</property>
  </filter>
  <filter id="filter13">
   <property name="channel">-1</property>
   <property name="mlt_service">panner</property>
   <property name="internal_added">237</property>
   <property name="start">0.5</property>
   <property name="disable">1</property>
  </filter>
  <filter id="filter14">
   <property name="iec_scale">0</property>
   <property name="prefix">meta.media.audio_level.</property>
   <property name="mlt_service">audiolevel</property>
   <property name="internal_added">237</property>
   <property name="dbpeak">1</property>
   <property name="disable">1</property>
  </filter>
 </tractor>
 <producer id="producer1" in="00:00:00.000" out="00:00:00.360">
  <property name="length">10</property>
  <property name="eof">pause</property>
  <property name="resource">0.5934295:C:/Users/2397681/Downloads/389511__bbrocer__digital-alarm-loop.wav</property>
  <property name="aspect_ratio">1</property>
  <property name="meta.media.nb_streams">1</property>
  <property name="meta.media.0.stream.type">audio</property>
  <property name="meta.media.0.codec.sample_fmt">s32</property>
  <property name="meta.media.0.codec.sample_rate">48000</property>
  <property name="meta.media.0.codec.channels">1</property>
  <property name="meta.media.0.codec.layout">mono</property>
  <property name="meta.media.0.codec.name">pcm_s24le</property>
  <property name="meta.media.0.codec.long_name">PCM signed 24-bit little-endian</property>
  <property name="meta.media.0.codec.bit_rate">1152000</property>
  <property name="meta.attr.date.markup">2017-04-19</property>
  <property name="meta.attr.encoder.markup">Adobe Audition 4.0.0.1815 (XMPDocOpsTemporal:2008.11.05)</property>
  <property name="meta.attr.creation_time.markup">12:31:55</property>
  <property name="meta.attr.time_reference.markup">258094</property>
  <property name="seekable">1</property>
  <property name="audio_index">0</property>
  <property name="video_index">-1</property>
  <property name="warp_speed">0.59343</property>
  <property name="warp_resource">C:/Users/2397681/Downloads/389511__bbrocer__digital-alarm-loop.wav</property>
  <property name="mlt_service">timewarp</property>
  <property name="kdenlive:control_uuid">{560beeaa-aeaf-4591-bb8b-b79c4b4868da}</property>
  <property name="astream">0</property>
  <property name="set.test_audio">0</property>
  <property name="set.test_image">1</property>
  <property name="kdenlive:id">8</property>
  <property name="warp_pitch">1</property>
 </producer>
 <producer id="producer2" in="00:00:00.000" out="00:00:00.360">
  <property name="length">10</property>
  <property name="eof">pause</property>
  <property name="resource">0.59343:C:/Users/2397681/Downloads/389511__bbrocer__digital-alarm-loop.wav</property>
  <property name="aspect_ratio">1</property>
  <property name="meta.media.nb_streams">1</property>
  <property name="meta.media.0.stream.type">audio</property>
  <property name="meta.media.0.codec.sample_fmt">s32</property>
  <property name="meta.media.0.codec.sample_rate">48000</property>
  <property name="meta.media.0.codec.channels">1</property>
  <property name="meta.media.0.codec.layout">mono</property>
  <property name="meta.media.0.codec.name">pcm_s24le</property>
  <property name="meta.media.0.codec.long_name">PCM signed 24-bit little-endian</property>
  <property name="meta.media.0.codec.bit_rate">1152000</property>
  <property name="meta.attr.date.markup">2017-04-19</property>
  <property name="meta.attr.encoder.markup">Adobe Audition 4.0.0.1815 (XMPDocOpsTemporal:2008.11.05)</property>
  <property name="meta.attr.creation_time.markup">12:31:55</property>
  <property name="meta.attr.time_reference.markup">258094</property>
  <property name="seekable">1</property>
  <property name="audio_index">0</property>
  <property name="video_index">-1</property>
  <property name="warp_speed">0.59343</property>
  <property name="warp_resource">C:/Users/2397681/Downloads/389511__bbrocer__digital-alarm-loop.wav</property>
  <property name="mlt_service">timewarp</property>
  <property name="kdenlive:control_uuid">{560beeaa-aeaf-4591-bb8b-b79c4b4868da}</property>
  <property name="astream">0</property>
  <property name="set.test_audio">0</property>
  <property name="set.test_image">1</property>
  <property name="kdenlive:id">8</property>
  <property name="warp_pitch">1</property>
 </producer>
 <producer id="producer3" in="00:00:00.000" out="00:00:00.360">
  <property name="length">10</property>
  <property name="eof">pause</property>
  <property name="resource">0.59343:C:/Users/2397681/Downloads/389511__bbrocer__digital-alarm-loop.wav</property>
  <property name="aspect_ratio">1</property>
  <property name="meta.media.nb_streams">1</property>
  <property name="meta.media.0.stream.type">audio</property>
  <property name="meta.media.0.codec.sample_fmt">s32</property>
  <property name="meta.media.0.codec.sample_rate">48000</property>
  <property name="meta.media.0.codec.channels">1</property>
  <property name="meta.media.0.codec.layout">mono</property>
  <property name="meta.media.0.codec.name">pcm_s24le</property>
  <property name="meta.media.0.codec.long_name">PCM signed 24-bit little-endian</property>
  <property name="meta.media.0.codec.bit_rate">1152000</property>
  <property name="meta.attr.date.markup">2017-04-19</property>
  <property name="meta.attr.encoder.markup">Adobe Audition 4.0.0.1815 (XMPDocOpsTemporal:2008.11.05)</property>
  <property name="meta.attr.creation_time.markup">12:31:55</property>
  <property name="meta.attr.time_reference.markup">258094</property>
  <property name="seekable">1</property>
  <property name="audio_index">0</property>
  <property name="video_index">-1</property>
  <property name="warp_speed">0.59343</property>
  <property name="warp_resource">C:/Users/2397681/Downloads/389511__bbrocer__digital-alarm-loop.wav</property>
  <property name="mlt_service">timewarp</property>
  <property name="kdenlive:control_uuid">{560beeaa-aeaf-4591-bb8b-b79c4b4868da}</property>
  <property name="astream">0</property>
  <property name="set.test_audio">0</property>
  <property name="set.test_image">1</property>
  <property name="kdenlive:id">8</property>
  <property name="warp_pitch">1</property>
 </producer>
 <producer id="producer4" in="00:00:00.000" out="00:00:00.360">
  <property name="length">10</property>
  <property name="eof">pause</property>
  <property name="resource">0.59343:C:/Users/2397681/Downloads/389511__bbrocer__digital-alarm-loop.wav</property>
  <property name="aspect_ratio">1</property>
  <property name="meta.media.nb_streams">1</property>
  <property name="meta.media.0.stream.type">audio</property>
  <property name="meta.media.0.codec.sample_fmt">s32</property>
  <property name="meta.media.0.codec.sample_rate">48000</property>
  <property name="meta.media.0.codec.channels">1</property>
  <property name="meta.media.0.codec.layout">mono</property>
  <property name="meta.media.0.codec.name">pcm_s24le</property>
  <property name="meta.media.0.codec.long_name">PCM signed 24-bit little-endian</property>
  <property name="meta.media.0.codec.bit_rate">1152000</property>
  <property name="meta.attr.date.markup">2017-04-19</property>
  <property name="meta.attr.encoder.markup">Adobe Audition 4.0.0.1815 (XMPDocOpsTemporal:2008.11.05)</property>
  <property name="meta.attr.creation_time.markup">12:31:55</property>
  <property name="meta.attr.time_reference.markup">258094</property>
  <property name="seekable">1</property>
  <property name="audio_index">0</property>
  <property name="video_index">-1</property>
  <property name="warp_speed">0.59343</property>
  <property name="warp_resource">C:/Users/2397681/Downloads/389511__bbrocer__digital-alarm-loop.wav</property>
  <property name="mlt_service">timewarp</property>
  <property name="kdenlive:control_uuid">{560beeaa-aeaf-4591-bb8b-b79c4b4868da}</property>
  <property name="astream">0</property>
  <property name="set.test_audio">0</property>
  <property name="set.test_image">1</property>
  <property name="kdenlive:id">8</property>
  <property name="warp_pitch">0</property>
 </producer>
 <chain id="chain8" out="00:02:04.160">
  <property name="length">3105</property>
  <property name="eof">pause</property>
  <property name="resource">C:/Users/2397681/Downloads/618895__sizeffects__home-alarm-keypad-beeps-close-perspective.wav</property>
  <property name="mlt_service">avformat-novalidate</property>
  <property name="seekable">1</property>
  <property name="audio_index">0</property>
  <property name="video_index">-1</property>
  <property name="astream">0</property>
  <property name="kdenlive:folderid">-1</property>
  <property name="kdenlive:id">10</property>
  <property name="kdenlive:control_uuid">{aabceff7-9096-4de6-8664-564f10d1a1fc}</property>
  <property name="kdenlive:clip_type">1</property>
  <property name="kdenlive:file_size">17918768</property>
  <property name="kdenlive:file_hash">30f496561bda254206474104f7b7c678</property>
  <property name="kdenlive:record_start_frame">504000</property>
  <property name="meta.media.nb_streams">1</property>
  <property name="meta.media.0.stream.type">audio</property>
  <property name="meta.media.0.codec.sample_fmt">s32</property>
  <property name="meta.media.0.codec.sample_rate">48000</property>
  <property name="meta.media.0.codec.channels">1</property>
  <property name="meta.media.0.codec.layout">mono</property>
  <property name="meta.media.0.codec.name">pcm_s24le</property>
  <property name="meta.media.0.codec.long_name">PCM signed 24-bit little-endian</property>
  <property name="meta.media.0.codec.bit_rate">1152000</property>
  <property name="meta.attr.comment.markup">zSPEED=25.000ND&#xd;
zTAKE=003&#xd;
zUBITS=00000000&#xd;
zSCENE=&#xd;
zTAPE=&#xd;
zCIRCLED=FALSE&#xd;
zTRK4=Tr2&#xd;
zNOTE=&#xd;
</property>
  <property name="meta.attr.encoded_by.markup">ZOOM F6</property>
  <property name="meta.attr.date.markup">2021-11-22</property>
  <property name="meta.attr.creation_time.markup">09:51:50</property>
  <property name="meta.attr.time_reference.markup">24192000</property>
  <property name="meta.attr.coding_history.markup">BaseHead Edited</property>
  <property name="xml">was here</property>
  <property name="mute_on_pause">0</property>
  <property name="set.test_audio">0</property>
  <property name="set.test_image">1</property>
 </chain>
 <chain id="chain9" out="00:01:12.040">
  <property name="length">1802</property>
  <property name="eof">pause</property>
  <property name="resource">C:/Users/2397681/Downloads/82076__kalashnikov_v2__00096_rs.wav</property>
  <property name="mlt_service">avformat-novalidate</property>
  <property name="seekable">1</property>
  <property name="audio_index">0</property>
  <property name="video_index">-1</property>
  <property name="astream">0</property>
  <property name="kdenlive:folderid">-1</property>
  <property name="kdenlive:id">11</property>
  <property name="kdenlive:control_uuid">{886ae97e-d8c5-42f8-84fe-8ea5c48e60d5}</property>
  <property name="kdenlive:clip_type">1</property>
  <property name="kdenlive:file_size">13845778</property>
  <property name="kdenlive:file_hash">9cb173e1ffa20e0efb0bf58a8fc84fba</property>
  <property name="kdenlive:record_start_frame">-1</property>
  <property name="meta.media.nb_streams">1</property>
  <property name="meta.media.0.stream.type">audio</property>
  <property name="meta.media.0.codec.sample_fmt">flt</property>
  <property name="meta.media.0.codec.sample_rate">48000</property>
  <property name="meta.media.0.codec.channels">1</property>
  <property name="meta.media.0.codec.layout">mono</property>
  <property name="meta.media.0.codec.name">pcm_f32le</property>
  <property name="meta.media.0.codec.long_name">PCM 32-bit floating point little-endian</property>
  <property name="meta.media.0.codec.bit_rate">1536000</property>
  <property name="meta.attr.date.markup">2009-10-19T10:05:52-05:00</property>
  <property name="xml">was here</property>
  <property name="mute_on_pause">0</property>
  <property name="set.test_audio">0</property>
  <property name="set.test_image">1</property>
 </chain>
 <chain id="chain10" out="00:01:59.960">
  <property name="length">3000</property>
  <property name="eof">pause</property>
  <property name="resource">C:/Users/2397681/Downloads/554726__soundensemble__720e-sfx-footsteps-boots-on-snow-21-01-17-0040.wav</property>
  <property name="mlt_service">avformat-novalidate</property>
  <property name="seekable">1</property>
  <property name="audio_index">0</property>
  <property name="video_index">-1</property>
  <property name="astream">0</property>
  <property name="kdenlive:folderid">-1</property>
  <property name="kdenlive:id">12</property>
  <property name="kdenlive:control_uuid">{fa827343-c7a9-480d-b508-43b9558d467c}</property>
  <property name="kdenlive:clip_type">1</property>
  <property name="kdenlive:file_size">138241168</property>
  <property name="kdenlive:file_hash">3e9b1fd99698e350496000f0a25ea379</property>
  <property name="kdenlive:record_start_frame">51128930</property>
  <property name="meta.media.nb_streams">1</property>
  <property name="meta.media.0.stream.type">audio</property>
  <property name="meta.media.0.codec.sample_fmt">s32</property>
  <property name="meta.media.0.codec.sample_rate">192000</property>
  <property name="meta.media.0.codec.channels">2</property>
  <property name="meta.media.0.codec.layout">independent</property>
  <property name="meta.media.0.codec.name">pcm_s24le</property>
  <property name="meta.media.0.codec.long_name">PCM signed 24-bit little-endian</property>
  <property name="meta.media.0.codec.bit_rate">9216000</property>
  <property name="meta.attr.encoded_by.markup">iZotope RX 7 Audio Editor</property>
  <property name="meta.attr.originator_reference.markup">USIZTC02YP17PLVCJ093158737202707</property>
  <property name="meta.attr.date.markup">2021-01-18</property>
  <property name="meta.attr.creation_time.markup">09:31:58</property>
  <property name="meta.attr.time_reference.markup">9816754560</property>
  <property name="meta.attr.coding_history.markup">T=XRI 00df&#xd;
XRI VER=0001&#xd;
MAKER=TASCAM&#xd;
MODEL=DR-100mk3&#xd;
FW VER=1.09&#xd;
SOURCE=1:UNI MIC,2:UNI MIC&#xd;
LEVEL=1:18.5,2:18.5&#xd;
A/D FILTER=1:SDL2,2:SDL2&#xd;
LOW CUT=1:OFF,2:OFF&#xd;
LEVEL CTRL=1:PEAK,2:PEAK&#xd;
LIMITER=1:OFF,2:OFF&#xd;
PAD SW=1:OFF,2:OFF&#xd;
</property>
  <property name="xml">was here</property>
  <property name="mute_on_pause">0</property>
  <property name="set.test_audio">0</property>
  <property name="set.test_image">1</property>
 </chain>
 <chain id="chain11" out="00:05:00.000">
  <property name="length">7501</property>
  <property name="eof">pause</property>
  <property name="resource">C:/Users/2397681/Downloads/626952__amaliazeichnerin__typing-on-computer-keyboard.mp3</property>
  <property name="mlt_service">avformat-novalidate</property>
  <property name="seekable">1</property>
  <property name="audio_index">0</property>
  <property name="video_index">-1</property>
  <property name="astream">0</property>
  <property name="kdenlive:folderid">-1</property>
  <property name="kdenlive:id">15</property>
  <property name="kdenlive:control_uuid">{92c02228-dfa3-413f-9a8e-bb1a8d91a81b}</property>
  <property name="kdenlive:clip_type">1</property>
  <property name="kdenlive:file_size">4790151</property>
  <property name="kdenlive:file_hash">95cf48921f82ea3aaf3bc0923157f285</property>
  <property name="kdenlive:record_start_frame">-1</property>
  <property name="meta.media.nb_streams">1</property>
  <property name="meta.media.0.stream.type">audio</property>
  <property name="meta.media.0.codec.sample_fmt">fltp</property>
  <property name="meta.media.0.codec.sample_rate">44100</property>
  <property name="meta.media.0.codec.channels">2</property>
  <property name="meta.media.0.codec.layout">stereo</property>
  <property name="meta.media.0.codec.name">mp3float</property>
  <property name="meta.media.0.codec.long_name">MP3 (MPEG audio layer 3)</property>
  <property name="meta.media.0.codec.bit_rate">127717</property>
  <property name="meta.attr.0.stream.encoder.markup">LAME3.98r</property>
  <property name="meta.attr.encoder.markup">LAME 64bits version 3.98.2 (http://www.mp3dev.org/)</property>
  <property name="xml">was here</property>
  <property name="mute_on_pause">0</property>
  <property name="set.test_audio">0</property>
  <property name="set.test_image">1</property>
 </chain>
 <playlist id="playlist8">
  <property name="kdenlive:audio_track">1</property>
  <entry in="00:00:00.000" out="00:00:00.360" producer="producer1">
   <property name="kdenlive:id">8</property>
  </entry>
  <entry in="00:00:00.000" out="00:00:00.360" producer="producer2">
   <property name="kdenlive:id">8</property>
  </entry>
  <entry in="00:00:00.000" out="00:00:00.360" producer="producer3">
   <property name="kdenlive:id">8</property>
  </entry>
  <entry in="00:00:00.000" out="00:00:00.360" producer="producer4">
   <property name="kdenlive:id">8</property>
  </entry>
  <entry in="00:00:03.280" out="00:00:03.600" producer="chain8">
   <property name="kdenlive:id">10</property>
  </entry>
  <blank length="00:00:00.760"/>
  <entry in="00:00:01.360" out="00:00:03.520" producer="chain9">
   <property name="kdenlive:id">11</property>
  </entry>
  <entry in="00:00:00.560" out="00:00:03.720" producer="chain10">
   <property name="kdenlive:id">12</property>
   <property name="kdenlive:activeeffect">0</property>
   <filter id="filter15">
    <property name="window">75</property>
    <property name="max_gain">20dB</property>
    <property name="level">00:00:00.560=-3</property>
    <property name="channel_mask">-1</property>
    <property name="mlt_service">volume</property>
    <property name="kdenlive_id">volume</property>
    <property name="kdenlive:collapsed">0</property>
   </filter>
  </entry>
  <entry in="00:00:11.600" out="00:00:14.400" producer="chain11">
   <property name="kdenlive:id">15</property>
  </entry>
  <entry in="00:00:00.560" out="00:00:03.720" producer="chain10">
   <property name="kdenlive:id">12</property>
   <filter id="filter16">
    <property name="window">75</property>
    <property name="max_gain">20dB</property>
    <property name="level">00:00:00.560=-3</property>
    <property name="channel_mask">-1</property>
    <property name="mlt_service">volume</property>
    <property name="kdenlive_id">volume</property>
    <property name="kdenlive:collapsed">0</property>
   </filter>
  </entry>
 </playlist>
 <playlist id="playlist9">
  <property name="kdenlive:audio_track">1</property>
 </playlist>
 <tractor id="tractor4" in="00:00:00.000" out="00:00:14.120">
  <property name="kdenlive:audio_track">1</property>
  <property name="kdenlive:trackheight">84</property>
  <property name="kdenlive:timeline_active">1</property>
  <property name="kdenlive:collapsed">0</property>
  <property name="kdenlive:thumbs_format"/>
  <property name="kdenlive:audio_rec"/>
  <track hide="video" producer="playlist8"/>
  <track hide="video" producer="playlist9"/>
  <transition id="transition0" in="00:00:09.880" out="00:00:09.920">
   <property name="a_track">0</property>
   <property name="b_track">1</property>
   <property name="duck_threshold">0</property>
   <property name="duck_attenuation">-12</property>
   <property name="duck_level">0</property>
   <property name="duck_fade_in">1500</property>
   <property name="duck_fade_out">250</property>
   <property name="prefix"/>
   <property name="mlt_service">mix</property>
   <property name="kdenlive_id">mix</property>
   <property name="kdenlive:mixcut">0</property>
   <property name="start">-1</property>
   <property name="accepts_blanks">1</property>
   <property name="reverse">0</property>
  </transition>
  <filter id="filter17">
   <property name="window">75</property>
   <property name="max_gain">20dB</property>
   <property name="channel_mask">-1</property>
   <property name="mlt_service">volume</property>
   <property name="internal_added">237</property>
   <property name="disable">1</property>
  </filter>
  <filter id="filter18">
   <property name="channel">-1</property>
   <property name="mlt_service">panner</property>
   <property name="internal_added">237</property>
   <property name="start">0.5</property>
   <property name="disable">1</property>
  </filter>
  <filter id="filter19">
   <property name="iec_scale">0</property>
   <property name="prefix">meta.media.audio_level.</property>
   <property name="mlt_service">audiolevel</property>
   <property name="internal_added">237</property>
   <property name="dbpeak">1</property>
   <property name="disable">1</property>
  </filter>
 </tractor>
 <chain id="chain12" out="00:02:37.960">
  <property name="length">3950</property>
  <property name="eof">pause</property>
  <property name="resource">C:/Users/2397681/Downloads/880639__johnlavine333__oblong-piano-source.wav</property>
  <property name="mlt_service">avformat-novalidate</property>
  <property name="seekable">1</property>
  <property name="audio_index">0</property>
  <property name="video_index">-1</property>
  <property name="astream">0</property>
  <property name="kdenlive:folderid">-1</property>
  <property name="kdenlive:id">7</property>
  <property name="kdenlive:control_uuid">{d286a554-eb83-4e46-bd13-3a4e58044d2b}</property>
  <property name="kdenlive:clip_type">1</property>
  <property name="kdenlive:file_size">27873358</property>
  <property name="kdenlive:file_hash">88caeea2b43f3730a98fa95ef88f8ada</property>
  <property name="kdenlive:record_start_frame">-1</property>
  <property name="meta.media.nb_streams">1</property>
  <property name="meta.media.0.stream.type">audio</property>
  <property name="meta.media.0.codec.sample_fmt">s16</property>
  <property name="meta.media.0.codec.sample_rate">44100</property>
  <property name="meta.media.0.codec.channels">2</property>
  <property name="meta.media.0.codec.layout">independent</property>
  <property name="meta.media.0.codec.name">pcm_s16le</property>
  <property name="meta.media.0.codec.long_name">PCM signed 16-bit little-endian</property>
  <property name="meta.media.0.codec.bit_rate">1411200</property>
  <property name="meta.attr.encoder.markup">Lavf56.40.101</property>
  <property name="xml">was here</property>
  <property name="mute_on_pause">0</property>
  <property name="set.test_audio">0</property>
  <property name="set.test_image">1</property>
 </chain>
 <playlist id="playlist10">
  <property name="kdenlive:audio_track">1</property>
  <entry in="00:00:16.960" out="00:00:36.880" producer="chain12">
   <property name="kdenlive:id">7</property>
  </entry>
 </playlist>
 <playlist id="playlist11">
  <property name="kdenlive:audio_track">1</property>
 </playlist>
 <tractor id="tractor5" in="00:00:00.000" out="00:00:19.920">
  <property name="kdenlive:audio_track">1</property>
  <property name="kdenlive:trackheight">84</property>
  <property name="kdenlive:timeline_active">1</property>
  <property name="kdenlive:collapsed">0</property>
  <property name="kdenlive:thumbs_format"/>
  <property name="kdenlive:audio_rec"/>
  <track hide="video" producer="playlist10"/>
  <track hide="video" producer="playlist11"/>
  <filter id="filter20">
   <property name="window">75</property>
   <property name="max_gain">20dB</property>
   <property name="channel_mask">-1</property>
   <property name="mlt_service">volume</property>
   <property name="internal_added">237</property>
   <property name="disable">1</property>
  </filter>
  <filter id="filter21">
   <property name="channel">-1</property>
   <property name="mlt_service">panner</property>
   <property name="internal_added">237</property>
   <property name="start">0.5</property>
   <property name="disable">1</property>
  </filter>
  <filter id="filter22">
   <property name="iec_scale">0</property>
   <property name="prefix">meta.media.audio_level.</property>
   <property name="mlt_service">audiolevel</property>
   <property name="internal_added">237</property>
   <property name="dbpeak">1</property>
   <property name="disable">1</property>
  </filter>
 </tractor>
 <playlist id="playlist12"/>
 <playlist id="playlist13"/>
 <tractor id="tractor6" in="00:00:00.000">
  <property name="kdenlive:trackheight">84</property>
  <property name="kdenlive:timeline_active">1</property>
  <property name="kdenlive:collapsed">0</property>
  <property name="kdenlive:thumbs_format"/>
  <property name="kdenlive:audio_rec"/>
  <track hide="audio" producer="playlist12"/>
  <track hide="audio" producer="playlist13"/>
 </tractor>
 <chain id="chain13" out="00:00:19.920">
  <property name="length">499</property>
  <property name="eof">pause</property>
  <property name="resource">C:/Users/2397681/Downloads/ezgif-7d9a937682ff9fbc (1).mp4</property>
  <property name="mlt_service">avformat-novalidate</property>
  <property name="seekable">1</property>
  <property name="audio_index">-1</property>
  <property name="video_index">0</property>
  <property name="vstream">0</property>
  <property name="kdenlive:control_uuid">{103b466b-169b-439d-9079-a832176d655d}</property>
  <property name="kdenlive:id">4</property>
  <property name="kdenlive:clip_type">2</property>
  <property name="kdenlive:file_size">2891294</property>
  <property name="kdenlive:file_hash">a9579c58ae319bb10bbf8ae96c48249a</property>
  <property name="kdenlive:folderid">-1</property>
  <property name="meta.media.nb_streams">1</property>
  <property name="meta.media.0.stream.type">video</property>
  <property name="meta.media.0.stream.frame_rate">25</property>
  <property name="meta.media.0.stream.sample_aspect_ratio">1</property>
  <property name="meta.media.0.codec.width">1280</property>
  <property name="meta.media.0.codec.height">720</property>
  <property name="meta.media.0.codec.rotate">0</property>
  <property name="meta.media.0.codec.pix_fmt">yuv420p</property>
  <property name="meta.media.0.codec.sample_aspect_ratio">1</property>
  <property name="meta.media.0.codec.colorspace">709</property>
  <property name="meta.media.0.codec.name">h264</property>
  <property name="meta.media.0.codec.long_name">H.264 / AVC / MPEG-4 AVC / MPEG-4 part 10</property>
  <property name="meta.media.0.codec.bit_rate">1156072</property>
  <property name="meta.attr.0.stream.handler_name.markup">VideoHandler</property>
  <property name="meta.attr.0.stream.encoder.markup">Lavc61.19.101 libx264</property>
  <property name="meta.attr.major_brand.markup">isom</property>
  <property name="meta.attr.minor_version.markup">512</property>
  <property name="meta.attr.compatible_brands.markup">isomiso2avc1mp41</property>
  <property name="meta.attr.encoder.markup">ezgif.com</property>
  <property name="meta.media.sample_aspect_num">1</property>
  <property name="meta.media.sample_aspect_den">1</property>
  <property name="meta.media.frame_rate_num">25</property>
  <property name="meta.media.frame_rate_den">1</property>
  <property name="meta.media.colorspace">709</property>
  <property name="meta.media.color_trc">2</property>
  <property name="meta.media.has_b_frames">2</property>
  <property name="meta.media.width">1280</property>
  <property name="meta.media.height">720</property>
  <property name="meta.media.aspect_ratio">1</property>
  <property name="meta.media.color_range">mpeg</property>
  <property name="xml">was here</property>
  <property name="mute_on_pause">0</property>
  <property name="meta.media.top_field_first">0</property>
  <property name="meta.media.progressive">1</property>
  <property name="set.test_audio">1</property>
  <property name="set.test_image">0</property>
 </chain>
 <playlist id="playlist14">
  <entry in="00:00:00.000" out="00:00:19.920" producer="chain13">
   <property name="kdenlive:id">4</property>
  </entry>
 </playlist>
 <playlist id="playlist15"/>
 <tractor id="tractor7" in="00:00:00.000" out="00:00:19.920">
  <property name="kdenlive:trackheight">84</property>
  <property name="kdenlive:timeline_active">1</property>
  <property name="kdenlive:collapsed">0</property>
  <property name="kdenlive:thumbs_format"/>
  <property name="kdenlive:audio_rec"/>
  <track hide="audio" producer="playlist14"/>
  <track hide="audio" producer="playlist15"/>
 </tractor>
 <tractor id="{9c7d29e7-6c08-4c59-be68-0f940cca3258}" in="00:00:00.000" out="00:00:20.520">
  <property name="kdenlive:uuid">{9c7d29e7-6c08-4c59-be68-0f940cca3258}</property>
  <property name="kdenlive:clipname">Séquence 1</property>
  <property name="kdenlive:sequenceproperties.hasAudio">1</property>
  <property name="kdenlive:sequenceproperties.hasVideo">1</property>
  <property name="kdenlive:sequenceproperties.activeTrack">1</property>
  <property name="kdenlive:sequenceproperties.tracksCount">8</property>
  <property name="kdenlive:sequenceproperties.documentuuid">{9c7d29e7-6c08-4c59-be68-0f940cca3258}</property>
  <property name="kdenlive:control_uuid">{9c7d29e7-6c08-4c59-be68-0f940cca3258}</property>
  <property name="kdenlive:duration">00:00:20.560</property>
  <property name="kdenlive:maxduration">514</property>
  <property name="kdenlive:producer_type">17</property>
  <property name="kdenlive:id">3</property>
  <property name="kdenlive:clip_type">0</property>
  <property name="kdenlive:file_size">0</property>
  <property name="kdenlive:folderid">2</property>
  <property name="kdenlive:sequenceproperties.audioTarget">1</property>
  <property name="kdenlive:sequenceproperties.disablepreview">0</property>
  <property name="kdenlive:sequenceproperties.position">513</property>
  <property name="kdenlive:sequenceproperties.scrollPos">0</property>
  <property name="kdenlive:sequenceproperties.tracks">4</property>
  <property name="kdenlive:sequenceproperties.verticalzoom">1</property>
  <property name="kdenlive:sequenceproperties.videoTarget">2</property>
  <property name="kdenlive:sequenceproperties.zonein">0</property>
  <property name="kdenlive:sequenceproperties.zoneout">3</property>
  <property name="kdenlive:sequenceproperties.zoom">5</property>
  <property name="kdenlive:sequenceproperties.groups">[
]
</property>
  <property name="kdenlive:sequenceproperties.guides">[
]
</property>
  <track producer="producer0"/>
  <track producer="tractor0"/>
  <track producer="tractor1"/>
  <track producer="tractor2"/>
  <track producer="tractor3"/>
  <track producer="tractor4"/>
  <track producer="tractor5"/>
  <track producer="tractor6"/>
  <track producer="tractor7"/>
  <transition id="transition1" in="00:00:16.960" out="00:00:19.920">
   <property name="a_track">7</property>
   <property name="b_track">8</property>
   <property name="factory">loader</property>
   <property name="resource"/>
   <property name="mlt_service">luma</property>
   <property name="kdenlive_id">dissolve</property>
   <property name="softness">0</property>
   <property name="reverse">1</property>
   <property name="alpha_over">0</property>
   <property name="fix_background_alpha">1</property>
  </transition>
  <transition id="transition2">
   <property name="a_track">0</property>
   <property name="b_track">1</property>
   <property name="duck_threshold">0</property>
   <property name="duck_attenuation">-12</property>
   <property name="duck_level">0</property>
   <property name="duck_fade_in">1500</property>
   <property name="duck_fade_out">250</property>
   <property name="prefix"/>
   <property name="mlt_service">mix</property>
   <property name="kdenlive_id">mix</property>
   <property name="internal_added">237</property>
   <property name="always_active">1</property>
   <property name="accepts_blanks">1</property>
   <property name="sum">1</property>
  </transition>
  <transition id="transition3">
   <property name="a_track">0</property>
   <property name="b_track">2</property>
   <property name="duck_threshold">0</property>
   <property name="duck_attenuation">-12</property>
   <property name="duck_level">0</property>
   <property name="duck_fade_in">1500</property>
   <property name="duck_fade_out">250</property>
   <property name="prefix"/>
   <property name="mlt_service">mix</property>
   <property name="kdenlive_id">mix</property>
   <property name="internal_added">237</property>
   <property name="always_active">1</property>
   <property name="accepts_blanks">1</property>
   <property name="sum">1</property>
  </transition>
  <transition id="transition4">
   <property name="a_track">0</property>
   <property name="b_track">3</property>
   <property name="duck_threshold">0</property>
   <property name="duck_attenuation">-12</property>
   <property name="duck_level">0</property>
   <property name="duck_fade_in">1500</property>
   <property name="duck_fade_out">250</property>
   <property name="prefix"/>
   <property name="mlt_service">mix</property>
   <property name="kdenlive_id">mix</property>
   <property name="internal_added">237</property>
   <property name="always_active">1</property>
   <property name="accepts_blanks">1</property>
   <property name="sum">1</property>
  </transition>
  <transition id="transition5">
   <property name="a_track">0</property>
   <property name="b_track">4</property>
   <property name="duck_threshold">0</property>
   <property name="duck_attenuation">-12</property>
   <property name="duck_level">0</property>
   <property name="duck_fade_in">1500</property>
   <property name="duck_fade_out">250</property>
   <property name="prefix"/>
   <property name="mlt_service">mix</property>
   <property name="kdenlive_id">mix</property>
   <property name="internal_added">237</property>
   <property name="always_active">1</property>
   <property name="accepts_blanks">1</property>
   <property name="sum">1</property>
  </transition>
  <transition id="transition6">
   <property name="a_track">0</property>
   <property name="b_track">5</property>
   <property name="duck_threshold">0</property>
   <property name="duck_attenuation">-12</property>
   <property name="duck_level">0</property>
   <property name="duck_fade_in">1500</property>
   <property name="duck_fade_out">250</property>
   <property name="prefix"/>
   <property name="mlt_service">mix</property>
   <property name="kdenlive_id">mix</property>
   <property name="internal_added">237</property>
   <property name="always_active">1</property>
   <property name="accepts_blanks">1</property>
   <property name="sum">1</property>
  </transition>
  <transition id="transition7">
   <property name="a_track">0</property>
   <property name="b_track">6</property>
   <property name="duck_threshold">0</property>
   <property name="duck_attenuation">-12</property>
   <property name="duck_level">0</property>
   <property name="duck_fade_in">1500</property>
   <property name="duck_fade_out">250</property>
   <property name="prefix"/>
   <property name="mlt_service">mix</property>
   <property name="kdenlive_id">mix</property>
   <property name="internal_added">237</property>
   <property name="always_active">1</property>
   <property name="accepts_blanks">1</property>
   <property name="sum">1</property>
  </transition>
  <transition id="transition8">
   <property name="a_track">0</property>
   <property name="b_track">7</property>
   <property name="compositing">0</property>
   <property name="distort">0</property>
   <property name="rotate_center">0</property>
   <property name="mlt_service">qtblend</property>
   <property name="kdenlive_id">qtblend</property>
   <property name="internal_added">237</property>
   <property name="always_active">1</property>
  </transition>
  <transition id="transition9">
   <property name="a_track">0</property>
   <property name="b_track">8</property>
   <property name="compositing">0</property>
   <property name="distort">0</property>
   <property name="rotate_center">0</property>
   <property name="mlt_service">qtblend</property>
   <property name="kdenlive_id">qtblend</property>
   <property name="internal_added">237</property>
   <property name="always_active">1</property>
  </transition>
  <filter id="filter23">
   <property name="window">75</property>
   <property name="max_gain">20dB</property>
   <property name="channel_mask">-1</property>
   <property name="mlt_service">volume</property>
   <property name="internal_added">237</property>
   <property name="disable">1</property>
  </filter>
  <filter id="filter24">
   <property name="channel">-1</property>
   <property name="mlt_service">panner</property>
   <property name="internal_added">237</property>
   <property name="start">0.5</property>
   <property name="disable">1</property>
  </filter>
 </tractor>
 <chain id="chain14" out="00:00:19.920">
  <property name="length">499</property>
  <property name="eof">pause</property>
  <property name="resource">C:/Users/2397681/Downloads/ezgif-7d9a937682ff9fbc (1).mp4</property>
  <property name="mlt_service">avformat</property>
  <property name="meta.media.nb_streams">1</property>
  <property name="meta.media.0.stream.type">video</property>
  <property name="meta.media.0.stream.frame_rate">25</property>
  <property name="meta.media.0.stream.sample_aspect_ratio">1</property>
  <property name="meta.media.0.codec.width">1280</property>
  <property name="meta.media.0.codec.height">720</property>
  <property name="meta.media.0.codec.rotate">0</property>
  <property name="meta.media.0.codec.pix_fmt">yuv420p</property>
  <property name="meta.media.0.codec.sample_aspect_ratio">1</property>
  <property name="meta.media.0.codec.colorspace">709</property>
  <property name="meta.media.0.codec.name">h264</property>
  <property name="meta.media.0.codec.long_name">H.264 / AVC / MPEG-4 AVC / MPEG-4 part 10</property>
  <property name="meta.media.0.codec.bit_rate">1156072</property>
  <property name="meta.attr.0.stream.handler_name.markup">VideoHandler</property>
  <property name="meta.attr.0.stream.encoder.markup">Lavc61.19.101 libx264</property>
  <property name="meta.attr.major_brand.markup">isom</property>
  <property name="meta.attr.minor_version.markup">512</property>
  <property name="meta.attr.compatible_brands.markup">isomiso2avc1mp41</property>
  <property name="meta.attr.encoder.markup">ezgif.com</property>
  <property name="seekable">1</property>
  <property name="meta.media.sample_aspect_num">1</property>
  <property name="meta.media.sample_aspect_den">1</property>
  <property name="audio_index">-1</property>
  <property name="video_index">0</property>
  <property name="vstream">0</property>
  <property name="meta.media.frame_rate_num">25</property>
  <property name="meta.media.frame_rate_den">1</property>
  <property name="meta.media.colorspace">709</property>
  <property name="meta.media.color_trc">2</property>
  <property name="meta.media.has_b_frames">2</property>
  <property name="meta.media.width">1280</property>
  <property name="meta.media.height">720</property>
  <property name="meta.media.aspect_ratio">1</property>
  <property name="meta.media.color_range">mpeg</property>
  <property name="meta.media.top_field_first">0</property>
  <property name="meta.media.progressive">1</property>
  <property name="kdenlive:control_uuid">{103b466b-169b-439d-9079-a832176d655d}</property>
  <property name="kdenlive:id">4</property>
  <property name="kdenlive:clip_type">2</property>
  <property name="kdenlive:file_size">2891294</property>
  <property name="kdenlive:file_hash">a9579c58ae319bb10bbf8ae96c48249a</property>
  <property name="kdenlive:folderid">-1</property>
  <property name="kdenlive:monitorPosition">33</property>
 </chain>
 <chain id="chain15" out="00:02:37.960">
  <property name="length">3950</property>
  <property name="eof">pause</property>
  <property name="resource">C:/Users/2397681/Downloads/880639__johnlavine333__oblong-piano-source.wav</property>
  <property name="mlt_service">avformat</property>
  <property name="meta.media.nb_streams">1</property>
  <property name="meta.media.0.stream.type">audio</property>
  <property name="meta.media.0.codec.sample_fmt">s16</property>
  <property name="meta.media.0.codec.sample_rate">44100</property>
  <property name="meta.media.0.codec.channels">2</property>
  <property name="meta.media.0.codec.layout">independent</property>
  <property name="meta.media.0.codec.name">pcm_s16le</property>
  <property name="meta.media.0.codec.long_name">PCM signed 16-bit little-endian</property>
  <property name="meta.media.0.codec.bit_rate">1411200</property>
  <property name="meta.attr.encoder.markup">Lavf56.40.101</property>
  <property name="seekable">1</property>
  <property name="audio_index">0</property>
  <property name="video_index">-1</property>
  <property name="astream">0</property>
  <property name="kdenlive:folderid">-1</property>
  <property name="kdenlive:id">7</property>
  <property name="kdenlive:control_uuid">{d286a554-eb83-4e46-bd13-3a4e58044d2b}</property>
  <property name="kdenlive:clip_type">1</property>
  <property name="kdenlive:file_size">27873358</property>
  <property name="kdenlive:file_hash">88caeea2b43f3730a98fa95ef88f8ada</property>
  <property name="kdenlive:record_start_frame">-1</property>
  <property name="kdenlive:kextractor">1</property>
  <property name="kdenlive:meta.extractor.Bitrate:">1411 kb/s</property>
  <property name="kdenlive:monitorPosition">806</property>
 </chain>
 <chain id="chain16" out="00:00:00.200">
  <property name="length">6</property>
  <property name="eof">pause</property>
  <property name="resource">C:/Users/2397681/Downloads/389511__bbrocer__digital-alarm-loop.wav</property>
  <property name="mlt_service">avformat</property>
  <property name="meta.media.nb_streams">1</property>
  <property name="meta.media.0.stream.type">audio</property>
  <property name="meta.media.0.codec.sample_fmt">s32</property>
  <property name="meta.media.0.codec.sample_rate">48000</property>
  <property name="meta.media.0.codec.channels">1</property>
  <property name="meta.media.0.codec.layout">mono</property>
  <property name="meta.media.0.codec.name">pcm_s24le</property>
  <property name="meta.media.0.codec.long_name">PCM signed 24-bit little-endian</property>
  <property name="meta.media.0.codec.bit_rate">1152000</property>
  <property name="meta.attr.date.markup">2017-04-19</property>
  <property name="meta.attr.encoder.markup">Adobe Audition 4.0.0.1815 (XMPDocOpsTemporal:2008.11.05)</property>
  <property name="meta.attr.creation_time.markup">12:31:55</property>
  <property name="meta.attr.time_reference.markup">258094</property>
  <property name="seekable">1</property>
  <property name="audio_index">0</property>
  <property name="video_index">-1</property>
  <property name="astream">0</property>
  <property name="kdenlive:folderid">-1</property>
  <property name="kdenlive:id">8</property>
  <property name="kdenlive:control_uuid">{560beeaa-aeaf-4591-bb8b-b79c4b4868da}</property>
  <property name="kdenlive:clip_type">1</property>
  <property name="kdenlive:file_size">41958</property>
  <property name="kdenlive:file_hash">819724f5e5630ec185790aa997656c24</property>
  <property name="kdenlive:record_start_frame">5376</property>
  <property name="kdenlive:kextractor">1</property>
  <property name="kdenlive:meta.extractor.Bitrate:">1152 kb/s</property>
  <property name="kdenlive:meta.extractor.Release Year:">2017</property>
  <property name="kdenlive:monitorPosition">0</property>
 </chain>
 <chain id="chain17" out="00:02:04.160">
  <property name="length">3105</property>
  <property name="eof">pause</property>
  <property name="resource">C:/Users/2397681/Downloads/618895__sizeffects__home-alarm-keypad-beeps-close-perspective.wav</property>
  <property name="mlt_service">avformat</property>
  <property name="meta.media.nb_streams">1</property>
  <property name="meta.media.0.stream.type">audio</property>
  <property name="meta.media.0.codec.sample_fmt">s32</property>
  <property name="meta.media.0.codec.sample_rate">48000</property>
  <property name="meta.media.0.codec.channels">1</property>
  <property name="meta.media.0.codec.layout">mono</property>
  <property name="meta.media.0.codec.name">pcm_s24le</property>
  <property name="meta.media.0.codec.long_name">PCM signed 24-bit little-endian</property>
  <property name="meta.media.0.codec.bit_rate">1152000</property>
  <property name="meta.attr.comment.markup">zSPEED=25.000ND&#xd;
zTAKE=003&#xd;
zUBITS=00000000&#xd;
zSCENE=&#xd;
zTAPE=&#xd;
zCIRCLED=FALSE&#xd;
zTRK4=Tr2&#xd;
zNOTE=&#xd;
</property>
  <property name="meta.attr.encoded_by.markup">ZOOM F6</property>
  <property name="meta.attr.date.markup">2021-11-22</property>
  <property name="meta.attr.creation_time.markup">09:51:50</property>
  <property name="meta.attr.time_reference.markup">24192000</property>
  <property name="meta.attr.coding_history.markup">BaseHead Edited</property>
  <property name="seekable">1</property>
  <property name="audio_index">0</property>
  <property name="video_index">-1</property>
  <property name="astream">0</property>
  <property name="kdenlive:folderid">-1</property>
  <property name="kdenlive:id">10</property>
  <property name="kdenlive:control_uuid">{aabceff7-9096-4de6-8664-564f10d1a1fc}</property>
  <property name="kdenlive:clip_type">1</property>
  <property name="kdenlive:file_size">17918768</property>
  <property name="kdenlive:file_hash">30f496561bda254206474104f7b7c678</property>
  <property name="kdenlive:record_start_frame">504000</property>
  <property name="kdenlive:kextractor">1</property>
  <property name="kdenlive:meta.extractor.Bitrate:">1152 kb/s</property>
  <property name="kdenlive:monitorPosition">0</property>
 </chain>
 <chain id="chain18" out="00:01:12.040">
  <property name="length">1802</property>
  <property name="eof">pause</property>
  <property name="resource">C:/Users/2397681/Downloads/82076__kalashnikov_v2__00096_rs.wav</property>
  <property name="mlt_service">avformat</property>
  <property name="meta.media.nb_streams">1</property>
  <property name="meta.media.0.stream.type">audio</property>
  <property name="meta.media.0.codec.sample_fmt">flt</property>
  <property name="meta.media.0.codec.sample_rate">48000</property>
  <property name="meta.media.0.codec.channels">1</property>
  <property name="meta.media.0.codec.layout">mono</property>
  <property name="meta.media.0.codec.name">pcm_f32le</property>
  <property name="meta.media.0.codec.long_name">PCM 32-bit floating point little-endian</property>
  <property name="meta.media.0.codec.bit_rate">1536000</property>
  <property name="meta.attr.date.markup">2009-10-19T10:05:52-05:00</property>
  <property name="seekable">1</property>
  <property name="audio_index">0</property>
  <property name="video_index">-1</property>
  <property name="astream">0</property>
  <property name="kdenlive:folderid">-1</property>
  <property name="kdenlive:id">11</property>
  <property name="kdenlive:control_uuid">{886ae97e-d8c5-42f8-84fe-8ea5c48e60d5}</property>
  <property name="kdenlive:clip_type">1</property>
  <property name="kdenlive:file_size">13845778</property>
  <property name="kdenlive:file_hash">9cb173e1ffa20e0efb0bf58a8fc84fba</property>
  <property name="kdenlive:record_start_frame">-1</property>
  <property name="kdenlive:kextractor">1</property>
  <property name="kdenlive:meta.extractor.Bitrate:">1536 kb/s</property>
  <property name="kdenlive:meta.extractor.Release Year:">2009</property>
  <property name="kdenlive:monitorPosition">127</property>
 </chain>
 <chain id="chain19" out="00:01:59.960">
  <property name="length">3000</property>
  <property name="eof">pause</property>
  <property name="resource">C:/Users/2397681/Downloads/554726__soundensemble__720e-sfx-footsteps-boots-on-snow-21-01-17-0040.wav</property>
  <property name="mlt_service">avformat</property>
  <property name="meta.media.nb_streams">1</property>
  <property name="meta.media.0.stream.type">audio</property>
  <property name="meta.media.0.codec.sample_fmt">s32</property>
  <property name="meta.media.0.codec.sample_rate">192000</property>
  <property name="meta.media.0.codec.channels">2</property>
  <property name="meta.media.0.codec.layout">independent</property>
  <property name="meta.media.0.codec.name">pcm_s24le</property>
  <property name="meta.media.0.codec.long_name">PCM signed 24-bit little-endian</property>
  <property name="meta.media.0.codec.bit_rate">9216000</property>
  <property name="meta.attr.encoded_by.markup">iZotope RX 7 Audio Editor</property>
  <property name="meta.attr.originator_reference.markup">USIZTC02YP17PLVCJ093158737202707</property>
  <property name="meta.attr.date.markup">2021-01-18</property>
  <property name="meta.attr.creation_time.markup">09:31:58</property>
  <property name="meta.attr.time_reference.markup">9816754560</property>
  <property name="meta.attr.coding_history.markup">T=XRI 00df&#xd;
XRI VER=0001&#xd;
MAKER=TASCAM&#xd;
MODEL=DR-100mk3&#xd;
FW VER=1.09&#xd;
SOURCE=1:UNI MIC,2:UNI MIC&#xd;
LEVEL=1:18.5,2:18.5&#xd;
A/D FILTER=1:SDL2,2:SDL2&#xd;
LOW CUT=1:OFF,2:OFF&#xd;
LEVEL CTRL=1:PEAK,2:PEAK&#xd;
LIMITER=1:OFF,2:OFF&#xd;
PAD SW=1:OFF,2:OFF&#xd;
</property>
  <property name="seekable">1</property>
  <property name="audio_index">0</property>
  <property name="video_index">-1</property>
  <property name="astream">0</property>
  <property name="kdenlive:folderid">-1</property>
  <property name="kdenlive:id">12</property>
  <property name="kdenlive:control_uuid">{fa827343-c7a9-480d-b508-43b9558d467c}</property>
  <property name="kdenlive:clip_type">1</property>
  <property name="kdenlive:file_size">138241168</property>
  <property name="kdenlive:file_hash">3e9b1fd99698e350496000f0a25ea379</property>
  <property name="kdenlive:record_start_frame">51128930</property>
  <property name="kdenlive:kextractor">1</property>
  <property name="kdenlive:meta.extractor.Bitrate:">9216 kb/s</property>
  <property name="kdenlive:monitorPosition">0</property>
 </chain>
 <chain id="chain20" out="00:00:27.760">
  <property name="length">695</property>
  <property name="eof">pause</property>
  <property name="resource">C:/Users/2397681/Downloads/837240__petercornell__smoke-exhale-blow-humdrum.wav</property>
  <property name="mlt_service">avformat</property>
  <property name="meta.media.nb_streams">1</property>
  <property name="meta.media.0.stream.type">audio</property>
  <property name="meta.media.0.codec.sample_fmt">s32</property>
  <property name="meta.media.0.codec.sample_rate">48000</property>
  <property name="meta.media.0.codec.channels">1</property>
  <property name="meta.media.0.codec.layout">mono</property>
  <property name="meta.media.0.codec.name">pcm_s24le</property>
  <property name="meta.media.0.codec.long_name">PCM signed 24-bit little-endian</property>
  <property name="meta.media.0.codec.bit_rate">1152000</property>
  <property name="meta.attr.encoded_by.markup">Pro Tools</property>
  <property name="meta.attr.originator_reference.markup">aa40QdPQSDQk</property>
  <property name="meta.attr.date.markup">2023-06-20</property>
  <property name="meta.attr.creation_time.markup">17:40:01</property>
  <property name="meta.attr.time_reference.markup">109225600</property>
  <property name="meta.attr.umid.markup">0x060A2B340101010501010F1013000000A76CAA90EAD38000D87D48007D779814</property>
  <property name="seekable">1</property>
  <property name="audio_index">0</property>
  <property name="video_index">-1</property>
  <property name="astream">0</property>
  <property name="kdenlive:folderid">-1</property>
  <property name="kdenlive:id">13</property>
  <property name="kdenlive:control_uuid">{6f2dbf0b-ef14-4866-94f4-dead868b8096}</property>
  <property name="kdenlive:clip_type">1</property>
  <property name="kdenlive:file_size">4025980</property>
  <property name="kdenlive:file_hash">aea9829f1968fb12d212e5c9dd67406e</property>
  <property name="kdenlive:record_start_frame">2275533</property>
  <property name="kdenlive:kextractor">1</property>
  <property name="kdenlive:meta.extractor.Bitrate:">1152 kb/s</property>
  <property name="kdenlive:monitorPosition">0</property>
 </chain>
 <chain id="chain21" out="00:04:15.120">
  <property name="length">6379</property>
  <property name="eof">pause</property>
  <property name="resource">C:/Users/2397681/Downloads/555053__brunoauzet__playground.wav</property>
  <property name="mlt_service">avformat</property>
  <property name="meta.media.nb_streams">1</property>
  <property name="meta.media.0.stream.type">audio</property>
  <property name="meta.media.0.codec.sample_fmt">s32</property>
  <property name="meta.media.0.codec.sample_rate">48000</property>
  <property name="meta.media.0.codec.channels">2</property>
  <property name="meta.media.0.codec.layout">independent</property>
  <property name="meta.media.0.codec.name">pcm_s24le</property>
  <property name="meta.media.0.codec.long_name">PCM signed 24-bit little-endian</property>
  <property name="meta.media.0.codec.bit_rate">2304000</property>
  <property name="meta.attr.encoded_by.markup">Pro Tools</property>
  <property name="meta.attr.originator_reference.markup">c40N3cqcU6jaaaGk</property>
  <property name="meta.attr.date.markup">2021-01-22</property>
  <property name="meta.attr.creation_time.markup">09:53:23</property>
  <property name="meta.attr.time_reference.markup">497006786</property>
  <property name="seekable">1</property>
  <property name="audio_index">0</property>
  <property name="video_index">-1</property>
  <property name="astream">0</property>
  <property name="kdenlive:folderid">-1</property>
  <property name="kdenlive:id">14</property>
  <property name="kdenlive:control_uuid">{935b4c12-b980-4689-a5a0-590503b9c74d}</property>
  <property name="kdenlive:clip_type">1</property>
  <property name="kdenlive:file_size">76175124</property>
  <property name="kdenlive:file_hash">ce207183c3e45d93b60e559a329c5ba2</property>
  <property name="kdenlive:record_start_frame">10354308</property>
  <property name="kdenlive:kextractor">1</property>
  <property name="kdenlive:meta.extractor.Bitrate:">2304 kb/s</property>
  <property name="kdenlive:monitorPosition">0</property>
 </chain>
 <chain id="chain22" out="00:05:00.000">
  <property name="length">7501</property>
  <property name="eof">pause</property>
  <property name="resource">C:/Users/2397681/Downloads/626952__amaliazeichnerin__typing-on-computer-keyboard.mp3</property>
  <property name="mlt_service">avformat</property>
  <property name="meta.media.nb_streams">1</property>
  <property name="meta.media.0.stream.type">audio</property>
  <property name="meta.media.0.codec.sample_fmt">fltp</property>
  <property name="meta.media.0.codec.sample_rate">44100</property>
  <property name="meta.media.0.codec.channels">2</property>
  <property name="meta.media.0.codec.layout">stereo</property>
  <property name="meta.media.0.codec.name">mp3float</property>
  <property name="meta.media.0.codec.long_name">MP3 (MPEG audio layer 3)</property>
  <property name="meta.media.0.codec.bit_rate">127717</property>
  <property name="meta.attr.0.stream.encoder.markup">LAME3.98r</property>
  <property name="meta.attr.encoder.markup">LAME 64bits version 3.98.2 (http://www.mp3dev.org/)</property>
  <property name="seekable">1</property>
  <property name="audio_index">0</property>
  <property name="video_index">-1</property>
  <property name="astream">0</property>
  <property name="kdenlive:folderid">-1</property>
  <property name="kdenlive:id">15</property>
  <property name="kdenlive:control_uuid">{92c02228-dfa3-413f-9a8e-bb1a8d91a81b}</property>
  <property name="kdenlive:clip_type">1</property>
  <property name="kdenlive:file_size">4790151</property>
  <property name="kdenlive:file_hash">95cf48921f82ea3aaf3bc0923157f285</property>
  <property name="kdenlive:record_start_frame">-1</property>
  <property name="kdenlive:kextractor">1</property>
  <property name="kdenlive:meta.extractor.Bitrate:">128 kb/s</property>
  <property name="kdenlive:monitorPosition">0</property>
 </chain>
 <chain id="chain23" out="00:02:02.960">
  <property name="length">3075</property>
  <property name="eof">pause</property>
  <property name="resource">C:/Users/2397681/Downloads/326404__mornedelport__reception-background-chatter-amb.wav</property>
  <property name="mlt_service">avformat</property>
  <property name="meta.media.nb_streams">1</property>
  <property name="meta.media.0.stream.type">audio</property>
  <property name="meta.media.0.codec.sample_fmt">s32</property>
  <property name="meta.media.0.codec.sample_rate">48000</property>
  <property name="meta.media.0.codec.channels">2</property>
  <property name="meta.media.0.codec.layout">independent</property>
  <property name="meta.media.0.codec.name">pcm_s24le</property>
  <property name="meta.media.0.codec.long_name">PCM signed 24-bit little-endian</property>
  <property name="meta.media.0.codec.bit_rate">2304000</property>
  <property name="meta.attr.encoded_by.markup">REAPER</property>
  <property name="meta.attr.date.markup">2015-10-27</property>
  <property name="meta.attr.creation_time.markup">12-42-29</property>
  <property name="meta.attr.time_reference.markup">0</property>
  <property name="seekable">1</property>
  <property name="audio_index">0</property>
  <property name="video_index">-1</property>
  <property name="astream">0</property>
  <property name="kdenlive:folderid">-1</property>
  <property name="kdenlive:id">16</property>
  <property name="kdenlive:control_uuid">{bfd0fcc5-e9fd-4941-85e6-3a1c97462af8}</property>
  <property name="kdenlive:clip_type">1</property>
  <property name="kdenlive:file_size">35424736</property>
  <property name="kdenlive:file_hash">f222c6c9eec407fab70e266748e8a88a</property>
  <property name="kdenlive:record_start_frame">-1</property>
  <property name="kdenlive:kextractor">1</property>
  <property name="kdenlive:meta.extractor.Bitrate:">2304 kb/s</property>
  <property name="kdenlive:monitorPosition">0</property>
 </chain>
 <chain id="chain24" out="00:01:43.040">
  <property name="length">2577</property>
  <property name="eof">pause</property>
  <property name="resource">C:/Users/2397681/Downloads/405224__soundsexciting__kids-fighting.wav</property>
  <property name="mlt_service">avformat</property>
  <property name="meta.media.nb_streams">1</property>
  <property name="meta.media.0.stream.type">audio</property>
  <property name="meta.media.0.codec.sample_fmt">flt</property>
  <property name="meta.media.0.codec.sample_rate">44100</property>
  <property name="meta.media.0.codec.channels">2</property>
  <property name="meta.media.0.codec.layout">independent</property>
  <property name="meta.media.0.codec.name">pcm_f32le</property>
  <property name="meta.media.0.codec.long_name">PCM 32-bit floating point little-endian</property>
  <property name="meta.media.0.codec.bit_rate">2822400</property>
  <property name="meta.attr.title.markup">Kids fighting</property>
  <property name="seekable">1</property>
  <property name="audio_index">0</property>
  <property name="video_index">-1</property>
  <property name="astream">0</property>
  <property name="kdenlive:folderid">-1</property>
  <property name="kdenlive:id">17</property>
  <property name="kdenlive:control_uuid">{8ca42706-a55c-4984-bed3-5b43a8e3d6b8}</property>
  <property name="kdenlive:clip_type">1</property>
  <property name="kdenlive:file_size">36372644</property>
  <property name="kdenlive:file_hash">267e038c3ca2a75434974a16657fbdda</property>
  <property name="kdenlive:record_start_frame">-1</property>
  <property name="kdenlive:kextractor">1</property>
  <property name="kdenlive:meta.extractor.Bitrate:">2822 kb/s</property>
  <property name="kdenlive:meta.extractor.Title:">Kids fighting</property>
  <property name="kdenlive:monitorPosition">0</property>
 </chain>
 <chain id="chain25" out="00:00:19.360">
  <property name="length">485</property>
  <property name="eof">pause</property>
  <property name="resource">C:/Users/2397681/Downloads/624477__valentinpetiteau__cloth-rustle-heavy-snap-clothespin.wav</property>
  <property name="mlt_service">avformat</property>
  <property name="meta.media.nb_streams">1</property>
  <property name="meta.media.0.stream.type">audio</property>
  <property name="meta.media.0.codec.sample_fmt">s32</property>
  <property name="meta.media.0.codec.sample_rate">96000</property>
  <property name="meta.media.0.codec.channels">1</property>
  <property name="meta.media.0.codec.layout">mono</property>
  <property name="meta.media.0.codec.name">pcm_s24le</property>
  <property name="meta.media.0.codec.long_name">PCM signed 24-bit little-endian</property>
  <property name="meta.media.0.codec.bit_rate">2304000</property>
  <property name="meta.attr.encoded_by.markup">iZotope RX 9 Advanced Audio Edi</property>
  <property name="meta.attr.originator_reference.markup">USIZT003358201786123811069178984</property>
  <property name="meta.attr.date.markup">2022-02-21</property>
  <property name="meta.attr.creation_time.markup">12:38:11</property>
  <property name="meta.attr.time_reference.markup">4258777457</property>
  <property name="meta.attr.coding_history.markup">A=PCM,F=96000,W=24,M=stereo,T=ZOOM Handy Recorder H5 XY5 STEREO            </property>
  <property name="seekable">1</property>
  <property name="audio_index">0</property>
  <property name="video_index">-1</property>
  <property name="astream">0</property>
  <property name="kdenlive:folderid">-1</property>
  <property name="kdenlive:id">18</property>
  <property name="kdenlive:control_uuid">{29fc1c5b-c778-4981-961a-e7225864bc6d}</property>
  <property name="kdenlive:clip_type">1</property>
  <property name="kdenlive:file_size">5619128</property>
  <property name="kdenlive:file_hash">fbd82c8b28d347492082c96dd668d837</property>
  <property name="kdenlive:record_start_frame">44362265</property>
  <property name="kdenlive:kextractor">1</property>
  <property name="kdenlive:meta.extractor.Bitrate:">2304 kb/s</property>
  <property name="kdenlive:monitorPosition">0</property>
 </chain>
 <chain id="chain26" out="00:01:02.600">
  <property name="length">1566</property>
  <property name="eof">pause</property>
  <property name="resource">C:/Users/2397681/Downloads/815791__lydgutten__strange-heartbeats.m4a</property>
  <property name="mlt_service">avformat</property>
  <property name="meta.media.nb_streams">1</property>
  <property name="meta.media.0.stream.type">audio</property>
  <property name="meta.media.0.codec.sample_fmt">fltp</property>
  <property name="meta.media.0.codec.sample_rate">48000</property>
  <property name="meta.media.0.codec.channels">2</property>
  <property name="meta.media.0.codec.layout">stereo</property>
  <property name="meta.media.0.codec.name">aac</property>
  <property name="meta.media.0.codec.long_name">AAC (Advanced Audio Coding)</property>
  <property name="meta.media.0.codec.bit_rate">256019</property>
  <property name="meta.attr.0.stream.creation_time.markup">2025-03-12T16:18:10.000000Z</property>
  <property name="meta.attr.0.stream.language.markup">eng</property>
  <property name="meta.attr.0.stream.handler_name.markup">SoundHandle</property>
  <property name="meta.attr.major_brand.markup">3gp4</property>
  <property name="meta.attr.minor_version.markup">0</property>
  <property name="meta.attr.compatible_brands.markup">isom3gp4</property>
  <property name="meta.attr.creation_time.markup">2025-03-12T16:18:10.000000Z</property>
  <property name="meta.attr.com.android.version.markup">14</property>
  <property name="seekable">1</property>
  <property name="audio_index">0</property>
  <property name="video_index">-1</property>
  <property name="astream">0</property>
  <property name="kdenlive:folderid">-1</property>
  <property name="kdenlive:id">19</property>
  <property name="kdenlive:control_uuid">{a51a7a32-d809-42e4-a504-a7b2527f745c}</property>
  <property name="kdenlive:clip_type">1</property>
  <property name="kdenlive:file_size">2056367</property>
  <property name="kdenlive:file_hash">e71893e3ab495fe957fd8bfe8a8eb0a7</property>
  <property name="kdenlive:record_start_frame">-1</property>
  <property name="kdenlive:kextractor">1</property>
  <property name="kdenlive:meta.extractor.Bitrate:">257 kb/s</property>
  <property name="kdenlive:monitorPosition">0</property>
 </chain>
 <chain id="chain27" out="00:00:10.960">
  <property name="length">275</property>
  <property name="eof">pause</property>
  <property name="resource">C:/Users/2397681/Downloads/863082__alexarje__bed-sheets-soundaction-104.wav</property>
  <property name="mlt_service">avformat</property>
  <property name="meta.media.nb_streams">1</property>
  <property name="meta.media.0.stream.type">audio</property>
  <property name="meta.media.0.codec.sample_fmt">s16</property>
  <property name="meta.media.0.codec.sample_rate">48000</property>
  <property name="meta.media.0.codec.channels">1</property>
  <property name="meta.media.0.codec.layout">mono</property>
  <property name="meta.media.0.codec.name">pcm_s16le</property>
  <property name="meta.media.0.codec.long_name">PCM signed 16-bit little-endian</property>
  <property name="meta.media.0.codec.bit_rate">768000</property>
  <property name="meta.attr.encoder.markup">Lavf58.76.100</property>
  <property name="seekable">1</property>
  <property name="audio_index">0</property>
  <property name="video_index">-1</property>
  <property name="astream">0</property>
  <property name="kdenlive:folderid">-1</property>
  <property name="kdenlive:id">20</property>
  <property name="kdenlive:control_uuid">{3ba702ba-8ce0-4010-9653-6119ef5239a5}</property>
  <property name="kdenlive:clip_type">1</property>
  <property name="kdenlive:file_size">1056846</property>
  <property name="kdenlive:file_hash">4373839fd48a56525b948d934712841f</property>
  <property name="kdenlive:record_start_frame">-1</property>
  <property name="kdenlive:kextractor">1</property>
  <property name="kdenlive:meta.extractor.Bitrate:">768 kb/s</property>
 </chain>
 <playlist id="main_bin">
  <property name="kdenlive:folder.-1.2">Séquences</property>
  <property name="kdenlive:sequenceFolder">2</property>
  <property name="kdenlive:docproperties.audioChannels">2</property>
  <property name="kdenlive:docproperties.binsort">0</property>
  <property name="kdenlive:docproperties.browserurl">C:/Users/2397681/Documents/</property>
  <property name="kdenlive:docproperties.documentid">1795022130492</property>
  <property name="kdenlive:docproperties.enableTimelineZone">0</property>
  <property name="kdenlive:docproperties.enableexternalproxy">0</property>
  <property name="kdenlive:docproperties.enableproxy">0</property>
  <property name="kdenlive:docproperties.externalproxyparams"/>
  <property name="kdenlive:docproperties.generateimageproxy">0</property>
  <property name="kdenlive:docproperties.generateproxy">0</property>
  <property name="kdenlive:docproperties.guidesCategories">[
    {
        "color": "#9b59b6",
        "comment": "Catégorie 1",
        "index": 0
    },
    {
        "color": "#3daee9",
        "comment": "Catégorie 2",
        "index": 1
    },
    {
        "color": "#1abc9c",
        "comment": "Catégorie 3",
        "index": 2
    },
    {
        "color": "#1cdc9a",
        "comment": "Catégorie 4",
        "index": 3
    },
    {
        "color": "#c9ce3b",
        "comment": "Catégorie 5",
        "index": 4
    },
    {
        "color": "#fdbc4b",
        "comment": "Catégorie 6",
        "index": 5
    },
    {
        "color": "#f39c1f",
        "comment": "Catégorie 7",
        "index": 6
    },
    {
        "color": "#f47750",
        "comment": "Catégorie 8",
        "index": 7
    },
    {
        "color": "#da4453",
        "comment": "Catégorie 9",
        "index": 8
    }
]
</property>
  <property name="kdenlive:docproperties.kdenliveversion">26.08.3</property>
  <property name="kdenlive:docproperties.patchversion">1</property>
  <property name="kdenlive:docproperties.previewextension"/>
  <property name="kdenlive:docproperties.previewparameters"/>
  <property name="kdenlive:docproperties.profile">atsc_720p_25</property>
  <property name="kdenlive:docproperties.proxyextension"/>
  <property name="kdenlive:docproperties.proxyimageminsize">2000</property>
  <property name="kdenlive:docproperties.proxyimagesize">800</property>
  <property name="kdenlive:docproperties.proxyminsize">1000</property>
  <property name="kdenlive:docproperties.proxyparams"/>
  <property name="kdenlive:docproperties.proxyresize">640</property>
  <property name="kdenlive:docproperties.seekOffset">30000</property>
  <property name="kdenlive:docproperties.sessionid">{97e59bd0-d468-45f0-9a0c-16fbd113e2ac}</property>
  <property name="kdenlive:docproperties.uuid">{9c7d29e7-6c08-4c59-be68-0f940cca3258}</property>
  <property name="kdenlive:docproperties.version">1.1</property>
  <property name="kdenlive:expandedFolders"/>
  <property name="kdenlive:binZoom">4</property>
  <property name="kdenlive:extraBins">project_bin:-1:0</property>
  <property name="kdenlive:documentnotes"/>
  <property name="kdenlive:documentnotesversion">2</property>
  <property name="kdenlive:docproperties.opensequences">{9c7d29e7-6c08-4c59-be68-0f940cca3258}</property>
  <property name="kdenlive:docproperties.activetimeline">{9c7d29e7-6c08-4c59-be68-0f940cca3258}</property>
  <property name="kdenlive:docproperties.layout">{
    "allDockWidgets": [
        {
            "lastCloseReason": 0,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 11,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": -1,
                "wasFloating": false
            },
            "uniqueName": "timeline"
        },
        {
            "lastCloseReason": 0,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 2,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 0,
                "wasFloating": false
            },
            "uniqueName": "project_bin"
        },
        {
            "lastCloseReason": 2,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 3,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 3,
                "wasFloating": false
            },
            "uniqueName": "library"
        },
        {
            "lastCloseReason": 2,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 12,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 2,
                "wasFloating": false
            },
            "uniqueName": "subtitles"
        },
        {
            "lastCloseReason": 2,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 4,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 2,
                "wasFloating": false
            },
            "uniqueName": "textedit"
        },
        {
            "lastCloseReason": 2,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 12,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 2,
                "wasFloating": false
            },
            "uniqueName": "timeremap"
        },
        {
            "lastCloseReason": 2,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 2,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 2,
                "wasFloating": false
            },
            "uniqueName": "markers"
        },
        {
            "lastCloseReason": 1,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 0,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 0,
                "wasFloating": false
            },
            "uniqueName": "screengrab"
        },
        {
            "lastCloseReason": 2,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 1,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 0,
                "wasFloating": false
            },
            "uniqueName": "audiospectrum"
        },
        {
            "lastCloseReason": 0,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 3,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 0,
                "wasFloating": false
            },
            "uniqueName": "clipmonitor"
        },
        {
            "lastCloseReason": 2,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 4,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 1,
                "wasFloating": false
            },
            "uniqueName": "projectmonitor"
        },
        {
            "lastCloseReason": 0,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 2,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 1,
                "wasFloating": false
            },
            "uniqueName": "clip_properties"
        },
        {
            "lastCloseReason": 2,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 4,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 4,
                "wasFloating": false
            },
            "uniqueName": "notes_widget"
        },
        {
            "lastCloseReason": 2,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 9,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 0,
                "wasFloating": false
            },
            "uniqueName": "media_browser"
        },
        {
            "lastCloseReason": 2,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 10,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 0,
                "wasFloating": false
            },
            "uniqueName": "onlineresources"
        },
        {
            "lastCloseReason": 0,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 12,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 1,
                "wasFloating": false
            },
            "uniqueName": "effect_stack"
        },
        {
            "lastCloseReason": 0,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 2,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": -1,
                "wasFloating": false
            },
            "uniqueName": "effect_list"
        },
        {
            "lastCloseReason": 0,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 2,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": -1,
                "wasFloating": false
            },
            "uniqueName": "transition_list"
        },
        {
            "lastCloseReason": 2,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 849,
                    "width": 905,
                    "x": 16,
                    "y": 82
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 2,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 2,
                "wasFloating": false
            },
            "uniqueName": "undo_history"
        },
        {
            "lastCloseReason": 2,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 12,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 2,
                "wasFloating": false
            },
            "uniqueName": "mixer"
        },
        {
            "lastCloseReason": 2,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 6,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 0,
                "wasFloating": false
            },
            "uniqueName": "vectorscope"
        },
        {
            "lastCloseReason": 2,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 5,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 0,
                "wasFloating": false
            },
            "uniqueName": "waveform"
        },
        {
            "lastCloseReason": 2,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 7,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 0,
                "wasFloating": false
            },
            "uniqueName": "rgb_parade"
        },
        {
            "lastCloseReason": 2,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 8,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 0,
                "wasFloating": false
            },
            "uniqueName": "histogram"
        }
    ],
    "closedDockWidgets": [
        "library",
        "subtitles",
        "textedit",
        "timeremap",
        "markers",
        "screengrab",
        "audiospectrum",
        "clip_properties",
        "notes_widget",
        "media_browser",
        "onlineresources",
        "effect_list",
        "transition_list",
        "undo_history",
        "mixer",
        "vectorscope",
        "waveform",
        "rgb_parade",
        "histogram"
    ],
    "floatingWindows": [],
    "mainWindows": [
        {
            "affinities": null,
            "geometry": {
                "height": 2054,
                "width": 3840,
                "x": 0,
                "y": 34
            },
            "isVisible": true,
            "multiSplitterLayout": {
                "frames": {
                    "4625": {
                        "currentTabIndex": 0,
                        "dockWidgets": [
                            "projectmonitor",
                            "textedit",
                            "notes_widget"
                        ],
                        "geometry": {
                            "height": 890,
                            "width": 1352,
                            "x": 2484,
                            "y": 0
                        },
                        "id": "4625",
                        "isNull": false,
                        "mainWindowUniqueName": "KdenliveKDDock",
                        "objectName": "projectmonitor",
                        "options": 0
                    },
                    "4722": {
                        "currentTabIndex": 0,
                        "dockWidgets": [
                            "project_bin",
                            "transition_list",
                            "effect_list",
                            "clip_properties",
                            "undo_history"
                        ],
                        "geometry": {
                            "height": 890,
                            "width": 1176,
                            "x": 0,
                            "y": 0
                        },
                        "id": "4722",
                        "isNull": false,
                        "mainWindowUniqueName": "KdenliveKDDock",
                        "objectName": "project_bin",
                        "options": 0
                    },
                    "4901": {
                        "currentTabIndex": 1,
                        "dockWidgets": [
                            "mixer",
                            "effect_stack",
                            "timeremap",
                            "subtitles"
                        ],
                        "geometry": {
                            "height": 1031,
                            "width": 782,
                            "x": 3054,
                            "y": 890
                        },
                        "id": "4901",
                        "isNull": false,
                        "mainWindowUniqueName": "KdenliveKDDock",
                        "objectName": "effect_stack",
                        "options": 0
                    },
                    "5037": {
                        "currentTabIndex": 0,
                        "dockWidgets": [
                            "clipmonitor",
                            "library"
                        ],
                        "geometry": {
                            "height": 890,
                            "width": 1308,
                            "x": 1176,
                            "y": 0
                        },
                        "id": "5037",
                        "isNull": false,
                        "mainWindowUniqueName": "KdenliveKDDock",
                        "objectName": "clipmonitor",
                        "options": 0
                    },
                    "5099": {
                        "currentTabIndex": 0,
                        "dockWidgets": [
                            "timeline"
                        ],
                        "geometry": {
                            "height": 1031,
                            "width": 3054,
                            "x": 0,
                            "y": 890
                        },
                        "id": "5099",
                        "isNull": false,
                        "mainWindowUniqueName": "KdenliveKDDock",
                        "objectName": "timeline",
                        "options": 0
                    }
                },
                "layout": {
                    "children": [
                        {
                            "children": [
                                {
                                    "children": [
                                        {
                                            "isContainer": false,
                                            "isVisible": false,
                                            "sizingInfo": {
                                                "geometry": {
                                                    "height": 440,
                                                    "width": 95,
                                                    "x": 0,
                                                    "y": 0
                                                },
                                                "maxSizeHint": {
                                                    "height": 524287,
                                                    "width": 524279
                                                },
                                                "minSize": {
                                                    "height": 90,
                                                    "width": 80
                                                },
                                                "percentageWithinParent": 0.0
                                            }
                                        },
                                        {
                                            "isContainer": false,
                                            "isVisible": false,
                                            "sizingInfo": {
                                                "geometry": {
                                                    "height": 440,
                                                    "width": 103,
                                                    "x": 0,
                                                    "y": 0
                                                },
                                                "maxSizeHint": {
                                                    "height": 524265,
                                                    "width": 524270
                                                },
                                                "minSize": {
                                                    "height": 90,
                                                    "width": 80
                                                },
                                                "percentageWithinParent": 0.0
                                            }
                                        },
                                        {
                                            "guestId": "4722",
                                            "isContainer": false,
                                            "isVisible": true,
                                            "sizingInfo": {
                                                "geometry": {
                                                    "height": 890,
                                                    "width": 1176,
                                                    "x": 0,
                                                    "y": 0
                                                },
                                                "maxSizeHint": {
                                                    "height": 524325,
                                                    "width": 524293
                                                },
                                                "minSize": {
                                                    "height": 295,
                                                    "width": 298
                                                },
                                                "percentageWithinParent": 0.306687565308255
                                            }
                                        },
                                        {
                                            "guestId": "5037",
                                            "isContainer": false,
                                            "isVisible": true,
                                            "sizingInfo": {
                                                "geometry": {
                                                    "height": 890,
                                                    "width": 1308,
                                                    "x": 1176,
                                                    "y": 0
                                                },
                                                "maxSizeHint": {
                                                    "height": 524325,
                                                    "width": 524293
                                                },
                                                "minSize": {
                                                    "height": 238,
                                                    "width": 326
                                                },
                                                "percentageWithinParent": 0.34117032392894464
                                            }
                                        },
                                        {
                                            "guestId": "4625",
                                            "isContainer": false,
                                            "isVisible": true,
                                            "sizingInfo": {
                                                "geometry": {
                                                    "height": 890,
                                                    "width": 1352,
                                                    "x": 2484,
                                                    "y": 0
                                                },
                                                "maxSizeHint": {
                                                    "height": 524325,
                                                    "width": 524293
                                                },
                                                "minSize": {
                                                    "height": 487,
                                                    "width": 674
                                                },
                                                "percentageWithinParent": 0.35214211076280044
                                            }
                                        },
                                        {
                                            "isContainer": false,
                                            "isVisible": false,
                                            "sizingInfo": {
                                                "geometry": {
                                                    "height": 440,
                                                    "width": 82,
                                                    "x": 1832,
                                                    "y": 0
                                                },
                                                "maxSizeHint": {
                                                    "height": 524287,
                                                    "width": 524287
                                                },
                                                "minSize": {
                                                    "height": 90,
                                                    "width": 80
                                                },
                                                "percentageWithinParent": 0.0
                                            }
                                        },
                                        {
                                            "isContainer": false,
                                            "isVisible": false,
                                            "sizingInfo": {
                                                "geometry": {
                                                    "height": 440,
                                                    "width": 167,
                                                    "x": 1747,
                                                    "y": 0
                                                },
                                                "maxSizeHint": {
                                                    "height": 524287,
                                                    "width": 524251
                                                },
                                                "minSize": {
                                                    "height": 90,
                                                    "width": 80
                                                },
                                                "percentageWithinParent": 0.0
                                            }
                                        },
                                        {
                                            "isContainer": false,
                                            "isVisible": false,
                                            "sizingInfo": {
                                                "geometry": {
                                                    "height": 440,
                                                    "width": 92,
                                                    "x": 1822,
                                                    "y": 0
                                                },
                                                "maxSizeHint": {
                                                    "height": 524287,
                                                    "width": 524287
                                                },
                                                "minSize": {
                                                    "height": 90,
                                                    "width": 80
                                                },
                                                "percentageWithinParent": 0.0
                                            }
                                        },
                                        {
                                            "isContainer": false,
                                            "isVisible": false,
                                            "sizingInfo": {
                                                "geometry": {
                                                    "height": 440,
                                                    "width": 81,
                                                    "x": 1833,
                                                    "y": 0
                                                },
                                                "maxSizeHint": {
                                                    "height": 524287,
                                                    "width": 524287
                                                },
                                                "minSize": {
                                                    "height": 90,
                                                    "width": 80
                                                },
                                                "percentageWithinParent": 0.0
                                            }
                                        },
                                        {
                                            "isContainer": false,
                                            "isVisible": false,
                                            "sizingInfo": {
                                                "geometry": {
                                                    "height": 508,
                                                    "width": 478,
                                                    "x": 1074,
                                                    "y": 0
                                                },
                                                "maxSizeHint": {
                                                    "height": 523905,
                                                    "width": 523960
                                                },
                                                "minSize": {
                                                    "height": 90,
                                                    "width": 80
                                                },
                                                "percentageWithinParent": 0.0
                                            }
                                        },
                                        {
                                            "isContainer": false,
                                            "isVisible": false,
                                            "sizingInfo": {
                                                "geometry": {
                                                    "height": 508,
                                                    "width": 378,
                                                    "x": 1536,
                                                    "y": 0
                                                },
                                                "maxSizeHint": {
                                                    "height": 524174,
                                                    "width": 524011
                                                },
                                                "minSize": {
                                                    "height": 90,
                                                    "width": 80
                                                },
                                                "percentageWithinParent": 0.0
                                            }
                                        }
                                    ],
                                    "isContainer": true,
                                    "isVisible": false,
                                    "orientation": 1,
                                    "sizingInfo": {
                                        "geometry": {
                                            "height": 890,
                                            "width": 3836,
                                            "x": 0,
                                            "y": 0
                                        },
                                        "maxSizeHint": {
                                            "height": 524325,
                                            "width": 1572879
                                        },
                                        "minSize": {
                                            "height": 487,
                                            "width": 1298
                                        },
                                        "percentageWithinParent": 0.46330036439354505
                                    }
                                },
                                {
                                    "children": [
                                        {
                                            "guestId": "5099",
                                            "isContainer": false,
                                            "isVisible": true,
                                            "sizingInfo": {
                                                "geometry": {
                                                    "height": 1031,
                                                    "width": 3054,
                                                    "x": 0,
                                                    "y": 0
                                                },
                                                "maxSizeHint": {
                                                    "height": 524338,
                                                    "width": 524300
                                                },
                                                "minSize": {
                                                    "height": 144,
                                                    "width": 95
                                                },
                                                "percentageWithinParent": 0.7961418143899895
                                            }
                                        },
                                        {
                                            "guestId": "4901",
                                            "isContainer": false,
                                            "isVisible": true,
                                            "sizingInfo": {
                                                "geometry": {
                                                    "height": 1031,
                                                    "width": 782,
                                                    "x": 3054,
                                                    "y": 0
                                                },
                                                "maxSizeHint": {
                                                    "height": 524325,
                                                    "width": 524293
                                                },
                                                "minSize": {
                                                    "height": 269,
                                                    "width": 336
                                                },
                                                "percentageWithinParent": 0.20385818561001043
                                            }
                                        }
                                    ],
                                    "isContainer": true,
                                    "isVisible": false,
                                    "orientation": 1,
                                    "sizingInfo": {
                                        "geometry": {
                                            "height": 1031,
                                            "width": 3836,
                                            "x": 0,
                                            "y": 890
                                        },
                                        "maxSizeHint": {
                                            "height": 524325,
                                            "width": 1048593
                                        },
                                        "minSize": {
                                            "height": 269,
                                            "width": 431
                                        },
                                        "percentageWithinParent": 0.536699635606455
                                    }
                                }
                            ],
                            "isContainer": true,
                            "isVisible": false,
                            "orientation": 2,
                            "sizingInfo": {
                                "geometry": {
                                    "height": 1921,
                                    "width": 3836,
                                    "x": 0,
                                    "y": 0
                                },
                                "maxSizeHint": {
                                    "height": 1048650,
                                    "width": 1048593
                                },
                                "minSize": {
                                    "height": 756,
                                    "width": 1298
                                },
                                "percentageWithinParent": 1.0
                            }
                        }
                    ],
                    "isContainer": true,
                    "isVisible": false,
                    "orientation": 1,
                    "sizingInfo": {
                        "geometry": {
                            "height": 1921,
                            "width": 3836,
                            "x": 0,
                            "y": 0
                        },
                        "maxSizeHint": {
                            "height": 16777215,
                            "width": 16777215
                        },
                        "minSize": {
                            "height": 90,
                            "width": 80
                        },
                        "percentageWithinParent": 0.0
                    }
                }
            },
            "normalGeometry": {
                "height": 0,
                "width": 0,
                "x": 0,
                "y": 0
            },
            "options": 0,
            "screenIndex": 0,
            "screenSize": {
                "height": 2160,
                "width": 3840
            },
            "uniqueName": "KdenliveKDDock",
            "windowState": 2
        }
    ],
    "screenInfo": [
        {
            "devicePixelRatio": 1.0,
            "geometry": {
                "height": 2160,
                "width": 3840,
                "x": 0,
                "y": 0
            },
            "index": 0,
            "name": "CB322QK"
        }
    ],
    "serializationVersion": 3
}</property>
  <property name="xml_retain">1</property>
  <entry in="00:00:00.000" out="00:00:00.000" producer="{9c7d29e7-6c08-4c59-be68-0f940cca3258}"/>
  <entry in="00:00:00.000" out="00:00:19.920" producer="chain14"/>
  <entry in="00:00:00.000" out="00:02:37.960" producer="chain15"/>
  <entry in="00:00:00.000" out="00:00:00.200" producer="chain16"/>
  <entry in="00:00:00.000" out="00:02:04.160" producer="chain17"/>
  <entry in="00:00:00.000" out="00:01:12.040" producer="chain18"/>
  <entry in="00:00:00.000" out="00:01:59.960" producer="chain19"/>
  <entry in="00:00:00.000" out="00:00:27.760" producer="chain20"/>
  <entry in="00:00:00.000" out="00:04:15.120" producer="chain21"/>
  <entry in="00:00:00.000" out="00:05:00.000" producer="chain22"/>
  <entry in="00:00:00.000" out="00:02:02.960" producer="chain23"/>
  <entry in="00:00:00.000" out="00:01:43.040" producer="chain24"/>
  <entry in="00:00:00.000" out="00:00:19.360" producer="chain25"/>
  <entry in="00:00:00.000" out="00:01:02.600" producer="chain26"/>
  <entry in="00:00:00.000" out="00:00:10.960" producer="chain27"/>
 </playlist>
 <tractor id="tractor8" in="00:00:00.000" out="00:00:20.520">
  <property name="kdenlive:projectTractor">1</property>
  <track in="00:00:00.000" out="00:00:20.520" producer="{9c7d29e7-6c08-4c59-be68-0f940cca3258}"/>
 </tractor>
</mlt>
