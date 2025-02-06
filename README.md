# SGM
**Root**:  
- **magic_number**: Type = Number  
- **version**: Type = Number  
- **material_count**: Type = Number  
- **material**:  
  - **id**: Type = Number  
  - **uv_count**: Type = Number  
  - **uv_set**:  
    - **texture_count**: Type = Number  
    - **texture**:  
      - **type_hint**: Type = Number  
      - **name_length**: Type = Number  
      - **file_name**: Type = String  
    - **color_count**: Type = Number  
    - **color**:  
      - **type_hint**: Type = Number  
      - **red**: Type = Number  
      - **green**: Type = Number  
      - **blue**: Type = Number  
      - **alpha**: Type = Number  

- **mesh_count**: Type = Number  
- **mesh**:  
  - **id**: Type = Number  
  - **material_id**: Type = Number  
  - **vertex_count**: Type = Number  
  - **uv_count**: Type = Number  
  - **color_channel_count**: Type = Number  
  - **has_tangents**: Type = Number  
  - **has_bones**: Type = Number  
  - **vertices**:  
    - **vertex_data**:  
      - **position**:  
        - **x**: Type = Number  
        - **y**: Type = Number  
        - **z**: Type = Number  
      - **normal**:  
        - **x**: Type = Number  
        - **y**: Type = Number  
        - **z**: Type = Number  
      - **uv_set**:  
        - **u**: Type = Number  
        - **v**: Type = Number  
      - **color_channel**:  
        - **value**: Type = Number  
      - **tangent**:  
        - **x**: Type = Number  
        - **y**: Type = Number  
        - **z**: Type = Number  
        - **bitangent_direction**: Type = Number  
      - **bone**:  
        - **weight_0**: Type = Number  
        - **weight_1**: Type = Number  
        - **weight_2**: Type = Number  
        - **weight_3**: Type = Number  
        - **index_0**: Type = Number  
        - **index_1**: Type = Number  
        - **index_2**: Type = Number  
        - **index_3**: Type = Number  
  - **index_count**: Type = Number  
  - **index_size**: Type = Number  
  - **indices**:  
    - **index**: Type = Number  

- **has_animation**: Type = Number  
- **animation**:  
  - **name_length**: Type = Number  
  - **filename**: Type = String  





# SGA
**Root**:  
- **magic_number**: Type = Number  
- **version**: Type = Number  
- **name_length**: Type = Number  
- **name**: Type = String  

**skeleton**:  
- **bone_count**: Type = Number  
- **bone**:  
  - **name_length**: Type = Number  
  - **name**: Type = String  
  - **position**:  
    - **x**: Type = Number  
    - **y**: Type = Number  
    - **z**: Type = Number  
  - **is_root**: Type = Number  
  - **child_count**: Type = Number  
  - **children**:  
    - **id**: Type = Number  

**animations**:  
- **animation_count**: Type = Number  
- **animation**:  
  - **name_length**: Type = Number  
  - **name**: Type = String  
  - **bone_count**: Type = Number  
  - **bone**:  
    - **id**: Type = Number  
    - **frame_count**: Type = Number  
    - **frame**:  
      - **timestamp**: Type = Number  
      - **position**:  
        - **x**: Type = Number  
        - **y**: Type = Number  
        - **z**: Type = Number  
      - **scale**:  
        - **x**: Type = Number  
        - **y**: Type = Number  
        - **z**: Type = Number  
      - **rotation**:  
        - **x**: Type = Number  
        - **y**: Type = Number  
        - **z**: Type = Number  
        - **w**: Type = Number  
