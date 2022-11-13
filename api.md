# Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`namespace `[`component`](#namespacecomponent) | 
`namespace `[`containers`](#namespacecontainers) | 
`namespace `[`ecs_system`](#namespaceecs__system) | 
`namespace `[`graphics`](#namespacegraphics) | 
`namespace `[`network`](#namespacenetwork) | 
`namespace `[`rtype`](#namespacertype) | 
`namespace `[`Systems`](#namespaceSystems) | 
`class `[`ClockTime`](#classClockTime) | 
`class `[`DLLoader`](#classDLLoader) | 
`class `[`Enet`](#classEnet) | 
`class `[`entity`](#classentity) | 
`class `[`registry::entity_manager_t`](#classregistry_1_1entity__manager__t) | 
`class `[`Error`](#classError) | 
`class `[`Raylib`](#classRaylib) | 
`class `[`registry`](#classregistry) | 
`class `[`sparse_array`](#classsparse__array) | 
`class `[`Test`](#classTest) | 
`struct `[`Vector2D`](#structVector2D) | 

# namespace `component` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`struct `[`component::acceleration`](#structcomponent_1_1acceleration) | 
`struct `[`component::clickable`](#structcomponent_1_1clickable) | 
`struct `[`component::controllable`](#structcomponent_1_1controllable) | 
`struct `[`component::damage`](#structcomponent_1_1damage) | 
`struct `[`component::drawable`](#structcomponent_1_1drawable) | 
`struct `[`component::network_id`](#structcomponent_1_1network__id) | 
`struct `[`component::parent`](#structcomponent_1_1parent) | 
`struct `[`component::player_type`](#structcomponent_1_1player__type) | 
`struct `[`component::position`](#structcomponent_1_1position) | 
`struct `[`component::scrolling`](#structcomponent_1_1scrolling) | 
`struct `[`component::sound`](#structcomponent_1_1sound) | 
`struct `[`component::velocity`](#structcomponent_1_1velocity) | 
`struct `[`component::weapon`](#structcomponent_1_1weapon) | 

# struct `component::acceleration` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public float `[`x`](#structcomponent_1_1acceleration_1a9051bb3e9b69c3d13f0697472f5f3842) | 
`public float `[`y`](#structcomponent_1_1acceleration_1ad1ed38e16b383170b26d51244bb6ee28) | 
`public inline  `[`acceleration`](#structcomponent_1_1acceleration_1af799d0267c1ef2e44188be36fc9862a8)`(float _x,float _y)` | 

## Members

#### `public float `[`x`](#structcomponent_1_1acceleration_1a9051bb3e9b69c3d13f0697472f5f3842) 

#### `public float `[`y`](#structcomponent_1_1acceleration_1ad1ed38e16b383170b26d51244bb6ee28) 

#### `public inline  `[`acceleration`](#structcomponent_1_1acceleration_1af799d0267c1ef2e44188be36fc9862a8)`(float _x,float _y)` 

# struct `component::clickable` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public float `[`width`](#structcomponent_1_1clickable_1af650ba64b03c19d1b051ab5be0c22fa3) | 
`public float `[`height`](#structcomponent_1_1clickable_1af9dbed3ae5574aabd25ec82c71df69c0) | 
`public actioner_t `[`action`](#structcomponent_1_1clickable_1ad6166a95f44d0f4e5c4879dc10d36134) | 
`public inline  `[`clickable`](#structcomponent_1_1clickable_1ac3658720ee36e9700849c75af772951b)`(float _width,float _height,actioner_t _action)` | 
`typedef `[`actioner_t`](#structcomponent_1_1clickable_1ad0a612d931df2b8fa7a0a1f477fe8ef3) | 

## Members

#### `public float `[`width`](#structcomponent_1_1clickable_1af650ba64b03c19d1b051ab5be0c22fa3) 

#### `public float `[`height`](#structcomponent_1_1clickable_1af9dbed3ae5574aabd25ec82c71df69c0) 

#### `public actioner_t `[`action`](#structcomponent_1_1clickable_1ad6166a95f44d0f4e5c4879dc10d36134) 

#### `public inline  `[`clickable`](#structcomponent_1_1clickable_1ac3658720ee36e9700849c75af772951b)`(float _width,float _height,actioner_t _action)` 

#### `typedef `[`actioner_t`](#structcomponent_1_1clickable_1ad0a612d931df2b8fa7a0a1f477fe8ef3) 

# struct `component::controllable` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public graphics::Keyboard `[`up`](#structcomponent_1_1controllable_1a050355e736668e97a8ad42d650a2f62b) | 
`public graphics::Keyboard `[`down`](#structcomponent_1_1controllable_1ac8be75cba03f3089ef14c2bb350c8ded) | 
`public graphics::Keyboard `[`left`](#structcomponent_1_1controllable_1ad88c1b97fe2277e239beab8cd05d7538) | 
`public graphics::Keyboard `[`right`](#structcomponent_1_1controllable_1a8663a72ddc584cf31108c112a445fc60) | 
`public graphics::Keyboard `[`shoot`](#structcomponent_1_1controllable_1af14db5fc5d4537d61a248c69ec7aa176) | 
`public sf::Keyboard::Key `[`keyUp`](#structcomponent_1_1controllable_1af9191caf199465f6103d223f63fb8592) | 
`public sf::Keyboard::Key `[`keyLeft`](#structcomponent_1_1controllable_1a4f7250b5a73391f46f7bf2ac61043422) | 
`public sf::Keyboard::Key `[`keyDown`](#structcomponent_1_1controllable_1a9abefe7efd746aea45cf32711c46fdcd) | 
`public sf::Keyboard::Key `[`keyRight`](#structcomponent_1_1controllable_1ab044e8c9f38739146b0e4a76ee123239) | 
`public inline  `[`controllable`](#structcomponent_1_1controllable_1a56bfb80542e981bbdff71fb2dbab5345)`(graphics::Keyboard _up,graphics::Keyboard _down,graphics::Keyboard _left,graphics::Keyboard _right,graphics::Keyboard _shoot)` | 

## Members

#### `public graphics::Keyboard `[`up`](#structcomponent_1_1controllable_1a050355e736668e97a8ad42d650a2f62b) 

#### `public graphics::Keyboard `[`down`](#structcomponent_1_1controllable_1ac8be75cba03f3089ef14c2bb350c8ded) 

#### `public graphics::Keyboard `[`left`](#structcomponent_1_1controllable_1ad88c1b97fe2277e239beab8cd05d7538) 

#### `public graphics::Keyboard `[`right`](#structcomponent_1_1controllable_1a8663a72ddc584cf31108c112a445fc60) 

#### `public graphics::Keyboard `[`shoot`](#structcomponent_1_1controllable_1af14db5fc5d4537d61a248c69ec7aa176) 

#### `public sf::Keyboard::Key `[`keyUp`](#structcomponent_1_1controllable_1af9191caf199465f6103d223f63fb8592) 

#### `public sf::Keyboard::Key `[`keyLeft`](#structcomponent_1_1controllable_1a4f7250b5a73391f46f7bf2ac61043422) 

#### `public sf::Keyboard::Key `[`keyDown`](#structcomponent_1_1controllable_1a9abefe7efd746aea45cf32711c46fdcd) 

#### `public sf::Keyboard::Key `[`keyRight`](#structcomponent_1_1controllable_1ab044e8c9f38739146b0e4a76ee123239) 

#### `public inline  `[`controllable`](#structcomponent_1_1controllable_1a56bfb80542e981bbdff71fb2dbab5345)`(graphics::Keyboard _up,graphics::Keyboard _down,graphics::Keyboard _left,graphics::Keyboard _right,graphics::Keyboard _shoot)` 

# struct `component::damage` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public int `[`val`](#structcomponent_1_1damage_1a88226417a237dfd4e0ac383d9d459901) | 
`public inline  `[`damage`](#structcomponent_1_1damage_1afd2da8c44c0497dde4223f5e4a691a10)`(int _val)` | 

## Members

#### `public int `[`val`](#structcomponent_1_1damage_1a88226417a237dfd4e0ac383d9d459901) 

#### `public inline  `[`damage`](#structcomponent_1_1damage_1afd2da8c44c0497dde4223f5e4a691a10)`(int _val)` 

# struct `component::drawable` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public graphics::DrawType `[`type`](#structcomponent_1_1drawable_1a5e3d8316c5f4ec5cfb7df8bd7a9edf0f) | 
`public std::string `[`img_path`](#structcomponent_1_1drawable_1a0dc8db8e9fe8f75577cee04229216775) | 
`public bool `[`scale`](#structcomponent_1_1drawable_1aee2b93b9d5a38ac10fa21277af7665f1) | 
`public float `[`img_scale_x`](#structcomponent_1_1drawable_1a4e243c7bef06cd50e19b17743d270c85) | 
`public float `[`img_scale_y`](#structcomponent_1_1drawable_1a7ace6529c8ade8f0332b1fa5daa37f59) | 
`public int `[`limit_x`](#structcomponent_1_1drawable_1afc107d4ad38aae30631c970f356d62e8) | 
`public int `[`limit_y`](#structcomponent_1_1drawable_1ad8ad62467357761305726f0a490e93b2) | 
`public int `[`framesCounter`](#structcomponent_1_1drawable_1a1c72065a5fd9be69b6aeb7f43b31cb1a) | 
`public int `[`framesSpeed`](#structcomponent_1_1drawable_1a163773e18186727b4cdf70807e57ca08) | 
`public int `[`currentFramex`](#structcomponent_1_1drawable_1ad6f7af64c478d8e6874668c213879246) | 
`public int `[`currentFramey`](#structcomponent_1_1drawable_1adc7256860004bcd8a101ba81aa36b89e) | 
`public std::string `[`font_path`](#structcomponent_1_1drawable_1aaa1b794dedc16e88867b596f462ce6ee) | 
`public std::string `[`text`](#structcomponent_1_1drawable_1a7b3ec64b5be9df3b71ad7d4513ce9cf3) | 
`public float `[`font_scale`](#structcomponent_1_1drawable_1ac3132328d9ca0397b8df0f39ee71f05b) | 
`public float `[`font_spacing`](#structcomponent_1_1drawable_1acb6bc4efbe6725c77e6a5d9c3092e42b) | 
`public float `[`rec_width`](#structcomponent_1_1drawable_1a01f9cdebc8e53bd6545f826bba329468) | 
`public float `[`rec_height`](#structcomponent_1_1drawable_1a00eae89d2942955daeb8259327345a26) | 
`public `[`graphics::color`](#structgraphics_1_1color)` `[`color`](#structcomponent_1_1drawable_1ac74ddba872c448bd03b03146bfd5fc89) | 
`public sf::RectangleShape `[`rec`](#structcomponent_1_1drawable_1a436efc8a637233e0d16960fdf6bdfcb8) | 
`public inline  `[`drawable`](#structcomponent_1_1drawable_1ad6d38539ccad633726db5a4da2cf8098)`()` | 
`public inline  `[`drawable`](#structcomponent_1_1drawable_1ab167f2a50c8ec10c6f7c35c5b8da4b4b)`(graphics::DrawType _type,std::string _img_path,bool _scale,float _img_scale_x,float _img_scale_y)` | 
`public inline  `[`drawable`](#structcomponent_1_1drawable_1ae9dec2f2d261c7c646669a125ccf82df)`(graphics::DrawType _type,std::string _font_path,std::string _text,float _scale,float _spacing,`[`graphics::color`](#structgraphics_1_1color)` _color)` | 
`public inline  `[`drawable`](#structcomponent_1_1drawable_1a5eb8676e606bd5d2273a938a7c7c6a01)`(graphics::DrawType _type,float _rec_width,float _rec_height,`[`graphics::color`](#structgraphics_1_1color)` _color)` | 
`public inline  `[`drawable`](#structcomponent_1_1drawable_1a0dcb9282482b3001773ae0de1e20ba48)`(graphics::DrawType _type,std::string _path,bool _scale,float _scale_x,float _scale_y,int _framex_nb,int _framey_nb,int _framesCounter,int _framesSpeed,int _currentFramex,int _currentFramey)` | 
`public inline  `[`drawable`](#structcomponent_1_1drawable_1a148f8b9c5812225ba17dda6905e33a5f)`(graphics::DrawType _type,std::string _path,bool _scale,float _scale_x,float _scale_y,int _framex_nb,int _framey_nb,int _currentFramex,int _currentFramey)` | 

## Members

#### `public graphics::DrawType `[`type`](#structcomponent_1_1drawable_1a5e3d8316c5f4ec5cfb7df8bd7a9edf0f) 

#### `public std::string `[`img_path`](#structcomponent_1_1drawable_1a0dc8db8e9fe8f75577cee04229216775) 

#### `public bool `[`scale`](#structcomponent_1_1drawable_1aee2b93b9d5a38ac10fa21277af7665f1) 

#### `public float `[`img_scale_x`](#structcomponent_1_1drawable_1a4e243c7bef06cd50e19b17743d270c85) 

#### `public float `[`img_scale_y`](#structcomponent_1_1drawable_1a7ace6529c8ade8f0332b1fa5daa37f59) 

#### `public int `[`limit_x`](#structcomponent_1_1drawable_1afc107d4ad38aae30631c970f356d62e8) 

#### `public int `[`limit_y`](#structcomponent_1_1drawable_1ad8ad62467357761305726f0a490e93b2) 

#### `public int `[`framesCounter`](#structcomponent_1_1drawable_1a1c72065a5fd9be69b6aeb7f43b31cb1a) 

#### `public int `[`framesSpeed`](#structcomponent_1_1drawable_1a163773e18186727b4cdf70807e57ca08) 

#### `public int `[`currentFramex`](#structcomponent_1_1drawable_1ad6f7af64c478d8e6874668c213879246) 

#### `public int `[`currentFramey`](#structcomponent_1_1drawable_1adc7256860004bcd8a101ba81aa36b89e) 

#### `public std::string `[`font_path`](#structcomponent_1_1drawable_1aaa1b794dedc16e88867b596f462ce6ee) 

#### `public std::string `[`text`](#structcomponent_1_1drawable_1a7b3ec64b5be9df3b71ad7d4513ce9cf3) 

#### `public float `[`font_scale`](#structcomponent_1_1drawable_1ac3132328d9ca0397b8df0f39ee71f05b) 

#### `public float `[`font_spacing`](#structcomponent_1_1drawable_1acb6bc4efbe6725c77e6a5d9c3092e42b) 

#### `public float `[`rec_width`](#structcomponent_1_1drawable_1a01f9cdebc8e53bd6545f826bba329468) 

#### `public float `[`rec_height`](#structcomponent_1_1drawable_1a00eae89d2942955daeb8259327345a26) 

#### `public `[`graphics::color`](#structgraphics_1_1color)` `[`color`](#structcomponent_1_1drawable_1ac74ddba872c448bd03b03146bfd5fc89) 

#### `public sf::RectangleShape `[`rec`](#structcomponent_1_1drawable_1a436efc8a637233e0d16960fdf6bdfcb8) 

#### `public inline  `[`drawable`](#structcomponent_1_1drawable_1ad6d38539ccad633726db5a4da2cf8098)`()` 

#### `public inline  `[`drawable`](#structcomponent_1_1drawable_1ab167f2a50c8ec10c6f7c35c5b8da4b4b)`(graphics::DrawType _type,std::string _img_path,bool _scale,float _img_scale_x,float _img_scale_y)` 

#### `public inline  `[`drawable`](#structcomponent_1_1drawable_1ae9dec2f2d261c7c646669a125ccf82df)`(graphics::DrawType _type,std::string _font_path,std::string _text,float _scale,float _spacing,`[`graphics::color`](#structgraphics_1_1color)` _color)` 

#### `public inline  `[`drawable`](#structcomponent_1_1drawable_1a5eb8676e606bd5d2273a938a7c7c6a01)`(graphics::DrawType _type,float _rec_width,float _rec_height,`[`graphics::color`](#structgraphics_1_1color)` _color)` 

#### `public inline  `[`drawable`](#structcomponent_1_1drawable_1a0dcb9282482b3001773ae0de1e20ba48)`(graphics::DrawType _type,std::string _path,bool _scale,float _scale_x,float _scale_y,int _framex_nb,int _framey_nb,int _framesCounter,int _framesSpeed,int _currentFramex,int _currentFramey)` 

#### `public inline  `[`drawable`](#structcomponent_1_1drawable_1a148f8b9c5812225ba17dda6905e33a5f)`(graphics::DrawType _type,std::string _path,bool _scale,float _scale_x,float _scale_y,int _framex_nb,int _framey_nb,int _currentFramex,int _currentFramey)` 

# struct `component::network_id` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public size_t `[`id`](#structcomponent_1_1network__id_1ab837fe576e12adac1773233f1c1345a8) | 
`public inline  `[`network_id`](#structcomponent_1_1network__id_1a9645d39f7dc56b9d32db534b4412a08b)`(size_t _id)` | 

## Members

#### `public size_t `[`id`](#structcomponent_1_1network__id_1ab837fe576e12adac1773233f1c1345a8) 

#### `public inline  `[`network_id`](#structcomponent_1_1network__id_1a9645d39f7dc56b9d32db534b4412a08b)`(size_t _id)` 

# struct `component::parent` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public `[`registry::entity_t`](#classentity)` `[`en`](#structcomponent_1_1parent_1aa22e95594f83acb5119b793fc917bdc1) | 
`public inline  `[`parent`](#structcomponent_1_1parent_1a52b8f8a1eb6d0e5caf52e56aab41d0e0)`(`[`registry::entity_t`](#classentity)` _en)` | 

## Members

#### `public `[`registry::entity_t`](#classentity)` `[`en`](#structcomponent_1_1parent_1aa22e95594f83acb5119b793fc917bdc1) 

#### `public inline  `[`parent`](#structcomponent_1_1parent_1a52b8f8a1eb6d0e5caf52e56aab41d0e0)`(`[`registry::entity_t`](#classentity)` _en)` 

# struct `component::player_type` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public int `[`type`](#structcomponent_1_1player__type_1ad3f542fd371e8f7e2a98a4d39c59a352) | 
`public inline  `[`player_type`](#structcomponent_1_1player__type_1aa9c3383423a0e2c8379d1014a86fe439)`(int _val)` | 

## Members

#### `public int `[`type`](#structcomponent_1_1player__type_1ad3f542fd371e8f7e2a98a4d39c59a352) 

#### `public inline  `[`player_type`](#structcomponent_1_1player__type_1aa9c3383423a0e2c8379d1014a86fe439)`(int _val)` 

# struct `component::position` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public float `[`x`](#structcomponent_1_1position_1ad81c687abab1ddbaa0bb3c46e360fc6e) | 
`public float `[`y`](#structcomponent_1_1position_1a5efb518f0f9e2d5f716942aafc69f1b9) | 
`public inline  `[`position`](#structcomponent_1_1position_1a47010ab7c06d8b30fb7e82cfe4f5737c)`(float _x,float _y)` | 

## Members

#### `public float `[`x`](#structcomponent_1_1position_1ad81c687abab1ddbaa0bb3c46e360fc6e) 

#### `public float `[`y`](#structcomponent_1_1position_1a5efb518f0f9e2d5f716942aafc69f1b9) 

#### `public inline  `[`position`](#structcomponent_1_1position_1a47010ab7c06d8b30fb7e82cfe4f5737c)`(float _x,float _y)` 

# struct `component::scrolling` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public float `[`limit`](#structcomponent_1_1scrolling_1ad7b39bd09c49314063a47b4e271d7116) | 
`public float `[`start`](#structcomponent_1_1scrolling_1a5367161dd1ce3c5fc6404f6a40e91cb3) | 
`public inline  `[`scrolling`](#structcomponent_1_1scrolling_1a9d8270ceb65b33fe08c0c62dca6289d6)`(float _l,float _s)` | 

## Members

#### `public float `[`limit`](#structcomponent_1_1scrolling_1ad7b39bd09c49314063a47b4e271d7116) 

#### `public float `[`start`](#structcomponent_1_1scrolling_1a5367161dd1ce3c5fc6404f6a40e91cb3) 

#### `public inline  `[`scrolling`](#structcomponent_1_1scrolling_1a9d8270ceb65b33fe08c0c62dca6289d6)`(float _l,float _s)` 

# struct `component::sound` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public std::string `[`song`](#structcomponent_1_1sound_1adea0784bd3a6e0c2274ef10b9cc7917b) | 
`public bool `[`looping`](#structcomponent_1_1sound_1a1b4b908bda93542dad9aa26f10bd1286) | 
`public inline  `[`sound`](#structcomponent_1_1sound_1ae3735203aa3c39b3d7a3747afa1ccf3e)`(std::string _song,bool _looping)` | 

## Members

#### `public std::string `[`song`](#structcomponent_1_1sound_1adea0784bd3a6e0c2274ef10b9cc7917b) 

#### `public bool `[`looping`](#structcomponent_1_1sound_1a1b4b908bda93542dad9aa26f10bd1286) 

#### `public inline  `[`sound`](#structcomponent_1_1sound_1ae3735203aa3c39b3d7a3747afa1ccf3e)`(std::string _song,bool _looping)` 

# struct `component::velocity` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public float `[`x`](#structcomponent_1_1velocity_1a3373a19e5aa3d54cd371a8b3ee89dbe4) | 
`public float `[`y`](#structcomponent_1_1velocity_1a2172daf5bf2f6a5ad0f030f481524f94) | 
`public inline  `[`velocity`](#structcomponent_1_1velocity_1a2d4d46bbc5c65a74381efd60b78a65a9)`(float _x,float _y)` | 

## Members

#### `public float `[`x`](#structcomponent_1_1velocity_1a3373a19e5aa3d54cd371a8b3ee89dbe4) 

#### `public float `[`y`](#structcomponent_1_1velocity_1a2172daf5bf2f6a5ad0f030f481524f94) 

#### `public inline  `[`velocity`](#structcomponent_1_1velocity_1a2d4d46bbc5c65a74381efd60b78a65a9)`(float _x,float _y)` 

# struct `component::weapon` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public `[`ClockTime`](#classClockTime)` `[`clock`](#structcomponent_1_1weapon_1a4170d44b80e1c40e0761f38bd037a02b) | 
`public int `[`type`](#structcomponent_1_1weapon_1abbd9d93537d1d0c3ee5cb8116150d521) | 
`public double `[`delay`](#structcomponent_1_1weapon_1a637a0ebf28aab50925fab2cab6dda1c0) | 
`public int `[`damage_val`](#structcomponent_1_1weapon_1ad7dc160990329467a90f7d77e70573ba) | 
`public float `[`vx`](#structcomponent_1_1weapon_1adb2a202fce360178def9c62bd896f294) | 
`public float `[`vy`](#structcomponent_1_1weapon_1a3c15986778b1ca4b267d74859a65543c) | 
`public inline  `[`weapon`](#structcomponent_1_1weapon_1a0cde1087996c626724b188945d6ce0b9)`(int _type,double _delay)` | 
`public inline void `[`shoot`](#structcomponent_1_1weapon_1a2c231cb7cfbe5a9e2d76314862b28e0b)`(`[`registry`](#classregistry)` & reg,`[`registry::entity_t`](#classentity)` p,float x,float y,std::shared_ptr< `[`network::INetworker`](#classnetwork_1_1INetworker)` > _net)` | 

## Members

#### `public `[`ClockTime`](#classClockTime)` `[`clock`](#structcomponent_1_1weapon_1a4170d44b80e1c40e0761f38bd037a02b) 

#### `public int `[`type`](#structcomponent_1_1weapon_1abbd9d93537d1d0c3ee5cb8116150d521) 

#### `public double `[`delay`](#structcomponent_1_1weapon_1a637a0ebf28aab50925fab2cab6dda1c0) 

#### `public int `[`damage_val`](#structcomponent_1_1weapon_1ad7dc160990329467a90f7d77e70573ba) 

#### `public float `[`vx`](#structcomponent_1_1weapon_1adb2a202fce360178def9c62bd896f294) 

#### `public float `[`vy`](#structcomponent_1_1weapon_1a3c15986778b1ca4b267d74859a65543c) 

#### `public inline  `[`weapon`](#structcomponent_1_1weapon_1a0cde1087996c626724b188945d6ce0b9)`(int _type,double _delay)` 

#### `public inline void `[`shoot`](#structcomponent_1_1weapon_1a2c231cb7cfbe5a9e2d76314862b28e0b)`(`[`registry`](#classregistry)` & reg,`[`registry::entity_t`](#classentity)` p,float x,float y,std::shared_ptr< `[`network::INetworker`](#classnetwork_1_1INetworker)` > _net)` 

# namespace `containers` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`class `[`containers::indexed_zipper`](#classcontainers_1_1indexed__zipper) | indexed_Zipper container to allow usage of iterator while handling sparse_arrays
`class `[`containers::indexed_zipper_iterator`](#classcontainers_1_1indexed__zipper__iterator) | 
`class `[`containers::zipper`](#classcontainers_1_1zipper) | Zipper container to allow usage of iterator while handling sparse_arrays.
`class `[`containers::zipper_iterator`](#classcontainers_1_1zipper__iterator) | 

# class `containers::indexed_zipper` 

indexed_Zipper container to allow usage of iterator while handling sparse_arrays

#### Parameters
* `Containers` (Some [sparse_array](#classsparse__array) of your choice)

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public inline  `[`indexed_zipper`](#classcontainers_1_1indexed__zipper_1a1ed5fff402cb7ef6767106237d1e2da4)`(Containers &... cs)` | Construct a new [indexed_zipper](#classcontainers_1_1indexed__zipper) object.
`public inline `[`iterator`](#classcontainers_1_1indexed__zipper__iterator)` `[`begin`](#classcontainers_1_1indexed__zipper_1a75d5034c93f3bd1bbc7f1bca7e0d9b9d)`()` | Return first iterator for [indexed_zipper](#classcontainers_1_1indexed__zipper) container.
`public inline `[`iterator`](#classcontainers_1_1indexed__zipper__iterator)` `[`end`](#classcontainers_1_1indexed__zipper_1ae08b3517143ee7c58334aa3ba2b985fc)`()` | Return end iterator for [indexed_zipper](#classcontainers_1_1indexed__zipper) container.
`public inline size_t `[`size`](#classcontainers_1_1indexed__zipper_1a04a8d157f3b57c30f7dc9e71c35f626a)`() const` | Getter for zipper's size.
`typedef `[`iterator`](#classcontainers_1_1indexed__zipper_1ae1046e55bae78a976fbb4a89a5f26129) | 
`typedef `[`iterator_tuple`](#classcontainers_1_1indexed__zipper_1a738b07a094b07fd38c5a9c2aa708f23b) | 

## Members

#### `public inline  `[`indexed_zipper`](#classcontainers_1_1indexed__zipper_1a1ed5fff402cb7ef6767106237d1e2da4)`(Containers &... cs)` 

Construct a new [indexed_zipper](#classcontainers_1_1indexed__zipper) object.

#### Parameters
* `cs` [sparse_array](#classsparse__array) lvalue references

#### `public inline `[`iterator`](#classcontainers_1_1indexed__zipper__iterator)` `[`begin`](#classcontainers_1_1indexed__zipper_1a75d5034c93f3bd1bbc7f1bca7e0d9b9d)`()` 

Return first iterator for [indexed_zipper](#classcontainers_1_1indexed__zipper) container.

#### Returns
iterator

#### `public inline `[`iterator`](#classcontainers_1_1indexed__zipper__iterator)` `[`end`](#classcontainers_1_1indexed__zipper_1ae08b3517143ee7c58334aa3ba2b985fc)`()` 

Return end iterator for [indexed_zipper](#classcontainers_1_1indexed__zipper) container.

#### Returns
iterator

#### `public inline size_t `[`size`](#classcontainers_1_1indexed__zipper_1a04a8d157f3b57c30f7dc9e71c35f626a)`() const` 

Getter for zipper's size.

#### Returns
size_t zipper's size

#### `typedef `[`iterator`](#classcontainers_1_1indexed__zipper_1ae1046e55bae78a976fbb4a89a5f26129) 

#### `typedef `[`iterator_tuple`](#classcontainers_1_1indexed__zipper_1a738b07a094b07fd38c5a9c2aa708f23b) 

# class `containers::indexed_zipper_iterator` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public inline  `[`indexed_zipper_iterator`](#classcontainers_1_1indexed__zipper__iterator_1ab175413e0ee74d604b9972e9c901fc04)`(iterator_tuple const & it_tuple,size_t max)` | Construct a new [indexed_zipper](#classcontainers_1_1indexed__zipper) iterator object.
`public inline  `[`indexed_zipper_iterator`](#classcontainers_1_1indexed__zipper__iterator_1a6b4e6b05bfbe37f7569e13dd8a04ab09)`()` | 
`public inline  `[`indexed_zipper_iterator`](#classcontainers_1_1indexed__zipper__iterator_1ae3b3b6c0a8a127cf6c7ae9353c2d9b25)`(`[`indexed_zipper_iterator`](#classcontainers_1_1indexed__zipper__iterator)` const & z)` | Construct a new [indexed_zipper](#classcontainers_1_1indexed__zipper) iterator object.
`public inline `[`indexed_zipper_iterator`](#classcontainers_1_1indexed__zipper__iterator)` & `[`operator=`](#classcontainers_1_1indexed__zipper__iterator_1a77e483daf6d427b5a189cc11d8354d3c)`(`[`indexed_zipper_iterator`](#classcontainers_1_1indexed__zipper__iterator)` const & z)` | 
`public inline `[`indexed_zipper_iterator`](#classcontainers_1_1indexed__zipper__iterator)` & `[`operator++`](#classcontainers_1_1indexed__zipper__iterator_1ac4ea9fc89cbf35da18c739915280fc16)`()` | Increment iterator and return previous value.
`public inline `[`indexed_zipper_iterator`](#classcontainers_1_1indexed__zipper__iterator)` `[`operator++`](#classcontainers_1_1indexed__zipper__iterator_1abecbdcdab3d2ef639c21b2b7c7079c26)`(int)` | Increment iterator and return current value.
`public inline `[`indexed_zipper_iterator`](#classcontainers_1_1indexed__zipper__iterator)` & `[`operator--`](#classcontainers_1_1indexed__zipper__iterator_1a1f6da04c02cc8b1e362a990724a5953a)`()` | Decrement iterator and return previous value.
`public inline `[`indexed_zipper_iterator`](#classcontainers_1_1indexed__zipper__iterator)` `[`operator--`](#classcontainers_1_1indexed__zipper__iterator_1af05796bee465483e981defcdb916880a)`(int)` | Decrement iterator and return current value.
`public inline void `[`set_value`](#classcontainers_1_1indexed__zipper__iterator_1a6ef2c96f85845c91dd1543ee1567daf7)`()` | 
`public inline reference `[`operator*`](#classcontainers_1_1indexed__zipper__iterator_1a52b66739c1de5043a0dc1ebb985e486d)`()` | Dereference iterator.
`public inline pointer `[`operator->`](#classcontainers_1_1indexed__zipper__iterator_1ab34e593a3ebda937b23e48365962c6fc)`()` | Dereference iterator.
`typedef `[`value_type`](#classcontainers_1_1indexed__zipper__iterator_1aa2647306d5cd5fe30cb1a81122319b17) | 
`typedef `[`reference`](#classcontainers_1_1indexed__zipper__iterator_1ac5254e0fdd47f0bb1719089ca944593d) | 
`typedef `[`pointer`](#classcontainers_1_1indexed__zipper__iterator_1ac1fb43ea6466bf98ddabec4841afeabd) | 
`typedef `[`difference_type`](#classcontainers_1_1indexed__zipper__iterator_1a3683735a3bcda90699e71a7475a2001e) | 
`typedef `[`iterator_category`](#classcontainers_1_1indexed__zipper__iterator_1a5223d0a109eb86ca57d0126d37c4dc9f) | 
`typedef `[`iterator_tuple`](#classcontainers_1_1indexed__zipper__iterator_1a342971799c87c66b4689d3ac4d0f0964) | 

## Members

#### `public inline  `[`indexed_zipper_iterator`](#classcontainers_1_1indexed__zipper__iterator_1ab175413e0ee74d604b9972e9c901fc04)`(iterator_tuple const & it_tuple,size_t max)` 

Construct a new [indexed_zipper](#classcontainers_1_1indexed__zipper) iterator object.

#### Parameters
* `it_tuple` iterator_tuple used to create first iterator 

* `max` Number of iterators available

#### `public inline  `[`indexed_zipper_iterator`](#classcontainers_1_1indexed__zipper__iterator_1a6b4e6b05bfbe37f7569e13dd8a04ab09)`()` 

#### `public inline  `[`indexed_zipper_iterator`](#classcontainers_1_1indexed__zipper__iterator_1ae3b3b6c0a8a127cf6c7ae9353c2d9b25)`(`[`indexed_zipper_iterator`](#classcontainers_1_1indexed__zipper__iterator)` const & z)` 

Construct a new [indexed_zipper](#classcontainers_1_1indexed__zipper) iterator object.

#### Parameters
* `z` [indexed_zipper_iterator](#classcontainers_1_1indexed__zipper__iterator) to copy

#### `public inline `[`indexed_zipper_iterator`](#classcontainers_1_1indexed__zipper__iterator)` & `[`operator=`](#classcontainers_1_1indexed__zipper__iterator_1a77e483daf6d427b5a189cc11d8354d3c)`(`[`indexed_zipper_iterator`](#classcontainers_1_1indexed__zipper__iterator)` const & z)` 

#### `public inline `[`indexed_zipper_iterator`](#classcontainers_1_1indexed__zipper__iterator)` & `[`operator++`](#classcontainers_1_1indexed__zipper__iterator_1ac4ea9fc89cbf35da18c739915280fc16)`()` 

Increment iterator and return previous value.

#### Returns
[indexed_zipper_iterator](#classcontainers_1_1indexed__zipper__iterator)

#### `public inline `[`indexed_zipper_iterator`](#classcontainers_1_1indexed__zipper__iterator)` `[`operator++`](#classcontainers_1_1indexed__zipper__iterator_1abecbdcdab3d2ef639c21b2b7c7079c26)`(int)` 

Increment iterator and return current value.

#### Returns
[indexed_zipper_iterator](#classcontainers_1_1indexed__zipper__iterator)

#### `public inline `[`indexed_zipper_iterator`](#classcontainers_1_1indexed__zipper__iterator)` & `[`operator--`](#classcontainers_1_1indexed__zipper__iterator_1a1f6da04c02cc8b1e362a990724a5953a)`()` 

Decrement iterator and return previous value.

#### Returns
[indexed_zipper_iterator](#classcontainers_1_1indexed__zipper__iterator)

#### `public inline `[`indexed_zipper_iterator`](#classcontainers_1_1indexed__zipper__iterator)` `[`operator--`](#classcontainers_1_1indexed__zipper__iterator_1af05796bee465483e981defcdb916880a)`(int)` 

Decrement iterator and return current value.

#### Returns
[indexed_zipper_iterator](#classcontainers_1_1indexed__zipper__iterator)

#### `public inline void `[`set_value`](#classcontainers_1_1indexed__zipper__iterator_1a6ef2c96f85845c91dd1543ee1567daf7)`()` 

#### `public inline reference `[`operator*`](#classcontainers_1_1indexed__zipper__iterator_1a52b66739c1de5043a0dc1ebb985e486d)`()` 

Dereference iterator.

#### Returns
reference

#### `public inline pointer `[`operator->`](#classcontainers_1_1indexed__zipper__iterator_1ab34e593a3ebda937b23e48365962c6fc)`()` 

Dereference iterator.

#### Returns
pointer

#### `typedef `[`value_type`](#classcontainers_1_1indexed__zipper__iterator_1aa2647306d5cd5fe30cb1a81122319b17) 

#### `typedef `[`reference`](#classcontainers_1_1indexed__zipper__iterator_1ac5254e0fdd47f0bb1719089ca944593d) 

#### `typedef `[`pointer`](#classcontainers_1_1indexed__zipper__iterator_1ac1fb43ea6466bf98ddabec4841afeabd) 

#### `typedef `[`difference_type`](#classcontainers_1_1indexed__zipper__iterator_1a3683735a3bcda90699e71a7475a2001e) 

#### `typedef `[`iterator_category`](#classcontainers_1_1indexed__zipper__iterator_1a5223d0a109eb86ca57d0126d37c4dc9f) 

#### `typedef `[`iterator_tuple`](#classcontainers_1_1indexed__zipper__iterator_1a342971799c87c66b4689d3ac4d0f0964) 

# class `containers::zipper` 

Zipper container to allow usage of iterator while handling sparse_arrays.

#### Parameters
* `Containers` (Some [sparse_array](#classsparse__array) of your choice)

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public inline  `[`zipper`](#classcontainers_1_1zipper_1a85e03314952524002fbe0aa2e8fc04b9)`(Containers &... cs)` | Construct a new zipper object.
`public inline `[`iterator`](#classcontainers_1_1zipper__iterator)` `[`begin`](#classcontainers_1_1zipper_1aaa9c13ae050a0fbcae80b75bfcc75454)`()` | Return first iterator for zipper container.
`public inline `[`iterator`](#classcontainers_1_1zipper__iterator)` `[`end`](#classcontainers_1_1zipper_1a33e914ddc870bad938576ad46569da1b)`()` | Return end iterator for zipper container.
`public inline size_t `[`size`](#classcontainers_1_1zipper_1afc8a5be3ffc7cf8e2b413fa67d213a7a)`() const` | Getter for zipper's size.
`typedef `[`iterator`](#classcontainers_1_1zipper_1a839bacbc53800294ef0cafdc79076613) | 
`typedef `[`iterator_tuple`](#classcontainers_1_1zipper_1a58f43daf7e915eda3ffeefbd1b9f6930) | 

## Members

#### `public inline  `[`zipper`](#classcontainers_1_1zipper_1a85e03314952524002fbe0aa2e8fc04b9)`(Containers &... cs)` 

Construct a new zipper object.

#### Parameters
* `cs` [sparse_array](#classsparse__array) lvalue references

#### `public inline `[`iterator`](#classcontainers_1_1zipper__iterator)` `[`begin`](#classcontainers_1_1zipper_1aaa9c13ae050a0fbcae80b75bfcc75454)`()` 

Return first iterator for zipper container.

#### Returns
iterator

#### `public inline `[`iterator`](#classcontainers_1_1zipper__iterator)` `[`end`](#classcontainers_1_1zipper_1a33e914ddc870bad938576ad46569da1b)`()` 

Return end iterator for zipper container.

#### Returns
iterator

#### `public inline size_t `[`size`](#classcontainers_1_1zipper_1afc8a5be3ffc7cf8e2b413fa67d213a7a)`() const` 

Getter for zipper's size.

#### Returns
size_t zipper's size

#### `typedef `[`iterator`](#classcontainers_1_1zipper_1a839bacbc53800294ef0cafdc79076613) 

#### `typedef `[`iterator_tuple`](#classcontainers_1_1zipper_1a58f43daf7e915eda3ffeefbd1b9f6930) 

# class `containers::zipper_iterator` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public inline  `[`zipper_iterator`](#classcontainers_1_1zipper__iterator_1a8cc553af6cd21f32e0a61344333377bf)`(iterator_tuple const & it_tuple,size_t max)` | Construct a new zipper iterator object.
`public inline  `[`zipper_iterator`](#classcontainers_1_1zipper__iterator_1a40f1c67ec6c2c29a33e5280a53b66a88)`()` | 
`public inline  `[`zipper_iterator`](#classcontainers_1_1zipper__iterator_1a57a7864c34b0c42916ccd4dd3dda8505)`(`[`zipper_iterator`](#classcontainers_1_1zipper__iterator)` const & z)` | Construct a new zipper iterator object.
`public inline `[`zipper_iterator`](#classcontainers_1_1zipper__iterator)` & `[`operator=`](#classcontainers_1_1zipper__iterator_1a97c991ffeabc86762643872a531df84d)`(`[`zipper_iterator`](#classcontainers_1_1zipper__iterator)` const & z)` | 
`public inline `[`zipper_iterator`](#classcontainers_1_1zipper__iterator)` & `[`operator++`](#classcontainers_1_1zipper__iterator_1a941467cbf36a7945688f988a64481e61)`()` | Increment iterator and return previous value.
`public inline `[`zipper_iterator`](#classcontainers_1_1zipper__iterator)` `[`operator++`](#classcontainers_1_1zipper__iterator_1a6411cbeed1833a854dce7e6f4b1f9383)`(int)` | Increment iterator and return current value.
`public inline `[`zipper_iterator`](#classcontainers_1_1zipper__iterator)` & `[`operator--`](#classcontainers_1_1zipper__iterator_1abed53ca32ff89eb37c301e282005f29b)`()` | Decrement iterator and return previous value.
`public inline `[`zipper_iterator`](#classcontainers_1_1zipper__iterator)` `[`operator--`](#classcontainers_1_1zipper__iterator_1a66bf796849e22c7d1c27e624a83c5f14)`(int)` | Decrement iterator and return current value.
`public inline void `[`set_value`](#classcontainers_1_1zipper__iterator_1a797726c8b9b8a5cf289669a12f7a8c9e)`()` | 
`public inline reference `[`operator*`](#classcontainers_1_1zipper__iterator_1a706791869d3c653e9b25451d05c1d7e8)`()` | Dereference iterator.
`public inline pointer `[`operator->`](#classcontainers_1_1zipper__iterator_1a046e7c6865d9824a1a6a8d6796ccc0b8)`()` | Dereference iterator.
`typedef `[`value_type`](#classcontainers_1_1zipper__iterator_1adcffc8b38227da427abec51c308c056d) | 
`typedef `[`reference`](#classcontainers_1_1zipper__iterator_1a5d84749226bb09b5e5cffe20d715f699) | 
`typedef `[`pointer`](#classcontainers_1_1zipper__iterator_1ae9e7f1366abf7e3e877dc32090cb5de9) | 
`typedef `[`difference_type`](#classcontainers_1_1zipper__iterator_1a1cfd50433882075d5c2f2a74ac42dc40) | 
`typedef `[`iterator_category`](#classcontainers_1_1zipper__iterator_1aa4e356fc97550cbccea01a5f9b13c824) | 
`typedef `[`iterator_tuple`](#classcontainers_1_1zipper__iterator_1a534086e4fc5fe56798ee84a162ada001) | 

## Members

#### `public inline  `[`zipper_iterator`](#classcontainers_1_1zipper__iterator_1a8cc553af6cd21f32e0a61344333377bf)`(iterator_tuple const & it_tuple,size_t max)` 

Construct a new zipper iterator object.

#### Parameters
* `it_tuple` iterator_tuple used to create first iterator 

* `max` Number of iterators available

#### `public inline  `[`zipper_iterator`](#classcontainers_1_1zipper__iterator_1a40f1c67ec6c2c29a33e5280a53b66a88)`()` 

#### `public inline  `[`zipper_iterator`](#classcontainers_1_1zipper__iterator_1a57a7864c34b0c42916ccd4dd3dda8505)`(`[`zipper_iterator`](#classcontainers_1_1zipper__iterator)` const & z)` 

Construct a new zipper iterator object.

#### Parameters
* `z` [zipper_iterator](#classcontainers_1_1zipper__iterator) to copy

#### `public inline `[`zipper_iterator`](#classcontainers_1_1zipper__iterator)` & `[`operator=`](#classcontainers_1_1zipper__iterator_1a97c991ffeabc86762643872a531df84d)`(`[`zipper_iterator`](#classcontainers_1_1zipper__iterator)` const & z)` 

#### `public inline `[`zipper_iterator`](#classcontainers_1_1zipper__iterator)` & `[`operator++`](#classcontainers_1_1zipper__iterator_1a941467cbf36a7945688f988a64481e61)`()` 

Increment iterator and return previous value.

#### Returns
[zipper_iterator](#classcontainers_1_1zipper__iterator)

#### `public inline `[`zipper_iterator`](#classcontainers_1_1zipper__iterator)` `[`operator++`](#classcontainers_1_1zipper__iterator_1a6411cbeed1833a854dce7e6f4b1f9383)`(int)` 

Increment iterator and return current value.

#### Returns
[zipper_iterator](#classcontainers_1_1zipper__iterator)

#### `public inline `[`zipper_iterator`](#classcontainers_1_1zipper__iterator)` & `[`operator--`](#classcontainers_1_1zipper__iterator_1abed53ca32ff89eb37c301e282005f29b)`()` 

Decrement iterator and return previous value.

#### Returns
[zipper_iterator](#classcontainers_1_1zipper__iterator)

#### `public inline `[`zipper_iterator`](#classcontainers_1_1zipper__iterator)` `[`operator--`](#classcontainers_1_1zipper__iterator_1a66bf796849e22c7d1c27e624a83c5f14)`(int)` 

Decrement iterator and return current value.

#### Returns
[zipper_iterator](#classcontainers_1_1zipper__iterator)

#### `public inline void `[`set_value`](#classcontainers_1_1zipper__iterator_1a797726c8b9b8a5cf289669a12f7a8c9e)`()` 

#### `public inline reference `[`operator*`](#classcontainers_1_1zipper__iterator_1a706791869d3c653e9b25451d05c1d7e8)`()` 

Dereference iterator.

#### Returns
reference

#### `public inline pointer `[`operator->`](#classcontainers_1_1zipper__iterator_1a046e7c6865d9824a1a6a8d6796ccc0b8)`()` 

Dereference iterator.

#### Returns
pointer

#### `typedef `[`value_type`](#classcontainers_1_1zipper__iterator_1adcffc8b38227da427abec51c308c056d) 

#### `typedef `[`reference`](#classcontainers_1_1zipper__iterator_1a5d84749226bb09b5e5cffe20d715f699) 

#### `typedef `[`pointer`](#classcontainers_1_1zipper__iterator_1ae9e7f1366abf7e3e877dc32090cb5de9) 

#### `typedef `[`difference_type`](#classcontainers_1_1zipper__iterator_1a1cfd50433882075d5c2f2a74ac42dc40) 

#### `typedef `[`iterator_category`](#classcontainers_1_1zipper__iterator_1aa4e356fc97550cbccea01a5f9b13c824) 

#### `typedef `[`iterator_tuple`](#classcontainers_1_1zipper__iterator_1a534086e4fc5fe56798ee84a162ada001) 

# namespace `ecs_system` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`class `[`ecs_system::control`](#classecs__system_1_1control) | 
`class `[`ecs_system::draw`](#classecs__system_1_1draw) | 

# class `ecs_system::control` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public inline  `[`control`](#classecs__system_1_1control_1a9623539736080ded85989f230f1822f1)`(sf::Event & event)` | 
`public inline  `[`~control`](#classecs__system_1_1control_1acf29bf46a11ec39013a817a4fb62c2c5)`()` | 
`public inline void `[`operator()`](#classecs__system_1_1control_1a04a2a6bd87a14c970be13e5f311ebea6)`(`[`registry`](#classregistry)` & reg)` | 

## Members

#### `public inline  `[`control`](#classecs__system_1_1control_1a9623539736080ded85989f230f1822f1)`(sf::Event & event)` 

#### `public inline  `[`~control`](#classecs__system_1_1control_1acf29bf46a11ec39013a817a4fb62c2c5)`()` 

#### `public inline void `[`operator()`](#classecs__system_1_1control_1a04a2a6bd87a14c970be13e5f311ebea6)`(`[`registry`](#classregistry)` & reg)` 

# class `ecs_system::draw` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public inline  `[`draw`](#classecs__system_1_1draw_1ac2b8aabe1acb8f332ff2ceda3e600565)`(sf::RenderWindow & window)` | 
`public inline  `[`~draw`](#classecs__system_1_1draw_1af487f173949f657bcf03482f782bfcaf)`()` | 
`public inline void `[`operator()`](#classecs__system_1_1draw_1a2e1f2267e6aea8d97a52392dc7cf55a5)`(`[`registry`](#classregistry)` & reg)` | 

## Members

#### `public inline  `[`draw`](#classecs__system_1_1draw_1ac2b8aabe1acb8f332ff2ceda3e600565)`(sf::RenderWindow & window)` 

#### `public inline  `[`~draw`](#classecs__system_1_1draw_1af487f173949f657bcf03482f782bfcaf)`()` 

#### `public inline void `[`operator()`](#classecs__system_1_1draw_1a2e1f2267e6aea8d97a52392dc7cf55a5)`(`[`registry`](#classregistry)` & reg)` 

# namespace `graphics` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`enum `[`Keyboard`](#IDisplay_8hpp_1aff95b66054bff8bb221db17f15893a64)            | 
`enum `[`MouseButton`](#IDisplay_8hpp_1aeb1623160f684ce34c74595def0b35f5)            | 
`enum `[`DrawType`](#IDisplay_8hpp_1ad31ec5e9e82ed8d0e9f5c16b89fd105d)            | 
`class `[`graphics::IDisplay`](#classgraphics_1_1IDisplay) | 
`struct `[`graphics::color`](#structgraphics_1_1color) | 

## Members

#### `enum `[`Keyboard`](#IDisplay_8hpp_1aff95b66054bff8bb221db17f15893a64) 

 Values                         | Descriptions                                
--------------------------------|---------------------------------------------
keyA            | 
keyB            | 
keyC            | 
keyD            | 
keyE            | 
keyF            | 
keyG            | 
keyH            | 
keyI            | 
keyJ            | 
keyK            | 
keyL            | 
keyM            | 
keyN            | 
keyO            | 
keyP            | 
keyQ            | 
keyR            | 
keyS            | 
keyT            | 
keyU            | 
keyV            | 
keyW            | 
keyX            | 
keyY            | 
keyZ            | 
keyUp            | 
keyDown            | 
keyRight            | 
keyLeft            | 
keyEnter            | 
keyDel            | 
keySpace            | 
key0            | 
key1            | 
key2            | 
key3            | 
key4            | 
key5            | 
key6            | 
key7            | 
key8            | 
key9            | 

#### `enum `[`MouseButton`](#IDisplay_8hpp_1aeb1623160f684ce34c74595def0b35f5) 

 Values                         | Descriptions                                
--------------------------------|---------------------------------------------
ButtonLeft            | 
ButtonRight            | 
ButtonMiddle            | 

#### `enum `[`DrawType`](#IDisplay_8hpp_1ad31ec5e9e82ed8d0e9f5c16b89fd105d) 

 Values                         | Descriptions                                
--------------------------------|---------------------------------------------
Rectangle            | 
Circle            | 
Text            | 
Image            | 
AnimImage            | 
Button            | 

# class `graphics::IDisplay` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public  `[`IDisplay`](#classgraphics_1_1IDisplay_1ade1b83a4b736f8c866be0a58b685ee99)`() = default` | 
`public inline virtual  `[`~IDisplay`](#classgraphics_1_1IDisplay_1a8842b34be9393e4083157dd33ac8d0aa)`()` | 
`public void `[`openWin`](#classgraphics_1_1IDisplay_1a42d4ac0840dd50629674739732c18158)`()` | 
`public int `[`getScreenWidth`](#classgraphics_1_1IDisplay_1a68e9af3e1a47f1547bc734c643526301)`()` | 
`public int `[`getScreenHeight`](#classgraphics_1_1IDisplay_1aecc5c67d9f7301c2501aa3be55de6d2b)`()` | 
`public void `[`setFps`](#classgraphics_1_1IDisplay_1a75686a31bb9195da5dcef3bdc581da24)`(int fps)` | 
`public bool `[`isOpen`](#classgraphics_1_1IDisplay_1ad3e8d7f8c2f6cd2f3ab549e36995054f)`()` | 
`public void `[`closeWin`](#classgraphics_1_1IDisplay_1ab42619fb6444a67ac7f4c25ed6df71d6)`()` | 
`public bool `[`pollEvent`](#classgraphics_1_1IDisplay_1ad2524a05717992ebad1f69394ce4c34d)`()` | 
`public void `[`beginDrawing`](#classgraphics_1_1IDisplay_1a422115304bc15272930fc91cfac942f1)`()` | 
`public void `[`clearBackground`](#classgraphics_1_1IDisplay_1aa83ce879ec863bc6d6afec6fb19928a8)`()` | 
`public void `[`draw`](#classgraphics_1_1IDisplay_1a7d87637abb600adbc1b716ad89d10967)`(`[`component::position`](#structcomponent_1_1position)` posComp,`[`component::drawable`](#structcomponent_1_1drawable)` drawComp)` | 
`public void `[`endDrawing`](#classgraphics_1_1IDisplay_1a20933b417f7b845cab5c2c3d327e2812)`()` | 
`public bool `[`isKeyPressed`](#classgraphics_1_1IDisplay_1a7496a199aa98a30da52e880e4dbf900d)`(Keyboard key)` | 
`public bool `[`isKeyBeingPressed`](#classgraphics_1_1IDisplay_1a64685751056794aeb7c2ee3cca05829f)`(Keyboard key)` | 
`public bool `[`isKeyReleased`](#classgraphics_1_1IDisplay_1a2e846357664409226f392f639b037260)`(Keyboard key)` | 
`public bool `[`isMouseButtonPressed`](#classgraphics_1_1IDisplay_1aa2c0a45707bde7c0fe6b31b0acee7a98)`(MouseButton button)` | 
`public bool `[`isMouseButtonBeingPressed`](#classgraphics_1_1IDisplay_1a278330d28bad9727887acb58d8898050)`(MouseButton button)` | 
`public bool `[`isMouseButtonReleased`](#classgraphics_1_1IDisplay_1a05a9a3fdae05afeaeee652cee37adcf7)`(MouseButton button)` | 
`public `[`Vector2D`](#structVector2D)`< float > `[`getMousePosition`](#classgraphics_1_1IDisplay_1a7125d9abf6dc9d100f80047e6e03a6f3)`()` | 
`public void `[`playSound`](#classgraphics_1_1IDisplay_1a35ee147040aedfc79ef7b9301f3cc26b)`(std::string path,bool looping)` | 
`public void `[`stopSound`](#classgraphics_1_1IDisplay_1adf53de91cee0a7cd9df6dfd5946b9d85)`(std::string path)` | 

## Members

#### `public  `[`IDisplay`](#classgraphics_1_1IDisplay_1ade1b83a4b736f8c866be0a58b685ee99)`() = default` 

#### `public inline virtual  `[`~IDisplay`](#classgraphics_1_1IDisplay_1a8842b34be9393e4083157dd33ac8d0aa)`()` 

#### `public void `[`openWin`](#classgraphics_1_1IDisplay_1a42d4ac0840dd50629674739732c18158)`()` 

#### `public int `[`getScreenWidth`](#classgraphics_1_1IDisplay_1a68e9af3e1a47f1547bc734c643526301)`()` 

#### `public int `[`getScreenHeight`](#classgraphics_1_1IDisplay_1aecc5c67d9f7301c2501aa3be55de6d2b)`()` 

#### `public void `[`setFps`](#classgraphics_1_1IDisplay_1a75686a31bb9195da5dcef3bdc581da24)`(int fps)` 

#### `public bool `[`isOpen`](#classgraphics_1_1IDisplay_1ad3e8d7f8c2f6cd2f3ab549e36995054f)`()` 

#### `public void `[`closeWin`](#classgraphics_1_1IDisplay_1ab42619fb6444a67ac7f4c25ed6df71d6)`()` 

#### `public bool `[`pollEvent`](#classgraphics_1_1IDisplay_1ad2524a05717992ebad1f69394ce4c34d)`()` 

#### `public void `[`beginDrawing`](#classgraphics_1_1IDisplay_1a422115304bc15272930fc91cfac942f1)`()` 

#### `public void `[`clearBackground`](#classgraphics_1_1IDisplay_1aa83ce879ec863bc6d6afec6fb19928a8)`()` 

#### `public void `[`draw`](#classgraphics_1_1IDisplay_1a7d87637abb600adbc1b716ad89d10967)`(`[`component::position`](#structcomponent_1_1position)` posComp,`[`component::drawable`](#structcomponent_1_1drawable)` drawComp)` 

#### `public void `[`endDrawing`](#classgraphics_1_1IDisplay_1a20933b417f7b845cab5c2c3d327e2812)`()` 

#### `public bool `[`isKeyPressed`](#classgraphics_1_1IDisplay_1a7496a199aa98a30da52e880e4dbf900d)`(Keyboard key)` 

#### `public bool `[`isKeyBeingPressed`](#classgraphics_1_1IDisplay_1a64685751056794aeb7c2ee3cca05829f)`(Keyboard key)` 

#### `public bool `[`isKeyReleased`](#classgraphics_1_1IDisplay_1a2e846357664409226f392f639b037260)`(Keyboard key)` 

#### `public bool `[`isMouseButtonPressed`](#classgraphics_1_1IDisplay_1aa2c0a45707bde7c0fe6b31b0acee7a98)`(MouseButton button)` 

#### `public bool `[`isMouseButtonBeingPressed`](#classgraphics_1_1IDisplay_1a278330d28bad9727887acb58d8898050)`(MouseButton button)` 

#### `public bool `[`isMouseButtonReleased`](#classgraphics_1_1IDisplay_1a05a9a3fdae05afeaeee652cee37adcf7)`(MouseButton button)` 

#### `public `[`Vector2D`](#structVector2D)`< float > `[`getMousePosition`](#classgraphics_1_1IDisplay_1a7125d9abf6dc9d100f80047e6e03a6f3)`()` 

#### `public void `[`playSound`](#classgraphics_1_1IDisplay_1a35ee147040aedfc79ef7b9301f3cc26b)`(std::string path,bool looping)` 

#### `public void `[`stopSound`](#classgraphics_1_1IDisplay_1adf53de91cee0a7cd9df6dfd5946b9d85)`(std::string path)` 

# struct `graphics::color` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public unsigned char `[`red`](#structgraphics_1_1color_1aedc31d808610af90389cf108bde94d86) | 
`public unsigned char `[`green`](#structgraphics_1_1color_1a3520538c9e242bc1b28284275bea031e) | 
`public unsigned char `[`blue`](#structgraphics_1_1color_1a89c4d65a18a1a52608682e6032ad85db) | 
`public unsigned char `[`alpha`](#structgraphics_1_1color_1a52d67786a1e68bcf4d013ab22c321901) | 

## Members

#### `public unsigned char `[`red`](#structgraphics_1_1color_1aedc31d808610af90389cf108bde94d86) 

#### `public unsigned char `[`green`](#structgraphics_1_1color_1a3520538c9e242bc1b28284275bea031e) 

#### `public unsigned char `[`blue`](#structgraphics_1_1color_1a89c4d65a18a1a52608682e6032ad85db) 

#### `public unsigned char `[`alpha`](#structgraphics_1_1color_1a52d67786a1e68bcf4d013ab22c321901) 

# namespace `network` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`enum `[`Command`](#INetworker_8hpp_1a4f49882eace57fc2599c944161f872a6)            | Differrents code that can be sent or received.
`class `[`network::INetworker`](#classnetwork_1_1INetworker) | Base class for networker.
`struct `[`network::datatrans`](#structnetwork_1_1datatrans) | class for data transmission

## Members

#### `enum `[`Command`](#INetworker_8hpp_1a4f49882eace57fc2599c944161f872a6) 

 Values                         | Descriptions                                
--------------------------------|---------------------------------------------
None            | 
CreatePlayer            | 
CreateTeamMate            | 
CreateEnnemy            | 
CreateMissile            | 
UpdatePosition            | 

Differrents code that can be sent or received.

# class `network::INetworker` 

Base class for networker.

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public inline  `[`INetworker`](#classnetwork_1_1INetworker_1a7026a0b619e21ed7828b54e0e9dd5a88)`(std::string ip,int port)` | Construct a new client.
`public inline  `[`INetworker`](#classnetwork_1_1INetworker_1a5f0beb4d4b0fe1958cfb742f40c2cd6b)`(int port)` | Construct a new server.
`public void `[`send_data`](#classnetwork_1_1INetworker_1aef33e147bdaf4d21aea28613ded4fe58)`()` | Send data to connected peer.
`public int `[`receive_data`](#classnetwork_1_1INetworker_1abf40ec464641221c4fa326404214efe6)`(int timeout)` | Get data that any peer sent.
`public inline  `[`~INetworker`](#classnetwork_1_1INetworker_1a34dea50bcb803d8ab4c76c9a31ee6b93)`()` | 
`public template<>`  <br/>`inline `[`INetworker`](#classnetwork_1_1INetworker)` & `[`operator<<`](#classnetwork_1_1INetworker_1a65d0eac5b6af6fe4ba7a50f014de9c8d)`(T val)` | Overload operator << to send data.
`public template<>`  <br/>`inline `[`INetworker`](#classnetwork_1_1INetworker)` & `[`operator>>`](#classnetwork_1_1INetworker_1ac5d674935d10b36262cc4ea2ebf52e73)`(T & val)` | Overload operator >> to receive data.
`public inline std::size_t `[`get_peer_id`](#classnetwork_1_1INetworker_1a282412c4f5e86c61c30f2ca7e18427b4)`() const` | Get the peer id object.
`public inline void `[`set_peer_id`](#classnetwork_1_1INetworker_1a12db8946723dfed7a46421b6acf8b931)`(std::size_t id)` | 
`protected std::string `[`_ip`](#classnetwork_1_1INetworker_1a557b7d5ac070e0bf0644fe60d68f6e0b) | 
`protected int `[`_port`](#classnetwork_1_1INetworker_1a68e1133c2169f6e8f262c9c0cc3f55cd) | 
`protected std::stringstream `[`stream`](#classnetwork_1_1INetworker_1adca5ad5f2989fa0ba818f982cf5538ad) | 
`protected std::size_t `[`peer_id`](#classnetwork_1_1INetworker_1a1f18f04662fb7d9d3ae29216065cfd92) | 

## Members

#### `public inline  `[`INetworker`](#classnetwork_1_1INetworker_1a7026a0b619e21ed7828b54e0e9dd5a88)`(std::string ip,int port)` 

Construct a new client.

#### Parameters
* `ip` Server's ip 

* `port` Server's port to connect

#### `public inline  `[`INetworker`](#classnetwork_1_1INetworker_1a5f0beb4d4b0fe1958cfb742f40c2cd6b)`(int port)` 

Construct a new server.

#### Parameters
* `port` Host's port to open

#### `public void `[`send_data`](#classnetwork_1_1INetworker_1aef33e147bdaf4d21aea28613ded4fe58)`()` 

Send data to connected peer.

#### Parameters
* `data` Data to send

#### `public int `[`receive_data`](#classnetwork_1_1INetworker_1abf40ec464641221c4fa326404214efe6)`(int timeout)` 

Get data that any peer sent.

#### Parameters
* `timeout` time to wait

#### Returns
void* Received data

#### `public inline  `[`~INetworker`](#classnetwork_1_1INetworker_1a34dea50bcb803d8ab4c76c9a31ee6b93)`()` 

#### `public template<>`  <br/>`inline `[`INetworker`](#classnetwork_1_1INetworker)` & `[`operator<<`](#classnetwork_1_1INetworker_1a65d0eac5b6af6fe4ba7a50f014de9c8d)`(T val)` 

Overload operator << to send data.

#### Parameters
* `T` Any variable type 

#### Parameters
* `val` Variable containig data to transfer 

#### Returns
[INetworker](#classnetwork_1_1INetworker)&

#### `public template<>`  <br/>`inline `[`INetworker`](#classnetwork_1_1INetworker)` & `[`operator>>`](#classnetwork_1_1INetworker_1ac5d674935d10b36262cc4ea2ebf52e73)`(T & val)` 

Overload operator >> to receive data.

#### Parameters
* `T` Any variable type 

#### Parameters
* `val` // Variable where to store data 

#### Returns
[INetworker](#classnetwork_1_1INetworker)&

#### `public inline std::size_t `[`get_peer_id`](#classnetwork_1_1INetworker_1a282412c4f5e86c61c30f2ca7e18427b4)`() const` 

Get the peer id object.

#### Returns
std::size_t

#### `public inline void `[`set_peer_id`](#classnetwork_1_1INetworker_1a12db8946723dfed7a46421b6acf8b931)`(std::size_t id)` 

#### `protected std::string `[`_ip`](#classnetwork_1_1INetworker_1a557b7d5ac070e0bf0644fe60d68f6e0b) 

#### `protected int `[`_port`](#classnetwork_1_1INetworker_1a68e1133c2169f6e8f262c9c0cc3f55cd) 

#### `protected std::stringstream `[`stream`](#classnetwork_1_1INetworker_1adca5ad5f2989fa0ba818f982cf5538ad) 

#### `protected std::size_t `[`peer_id`](#classnetwork_1_1INetworker_1a1f18f04662fb7d9d3ae29216065cfd92) 

# struct `network::datatrans` 

class for data transmission

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public Command `[`_code`](#structnetwork_1_1datatrans_1a865a2e39d7e0f5e5769eb80fd9373283) | 
`public size_t `[`_id`](#structnetwork_1_1datatrans_1adc842714ffc3ff39f768852a5c4e0069) | 
`public int `[`_type`](#structnetwork_1_1datatrans_1a17c6e797b84c1f1dfee162e0ac3cd9f7) | 
`public float `[`_x`](#structnetwork_1_1datatrans_1a39c96eb7ca7054b7740f44783745a478) | 
`public float `[`_y`](#structnetwork_1_1datatrans_1a62b0f538e286134bec7e4b91d6bf8e19) | 
`public float `[`_zx`](#structnetwork_1_1datatrans_1aa16efafd5c445b558e610d87c90eadd8) | 
`public float `[`_zy`](#structnetwork_1_1datatrans_1a8a80b19467290e100a5d7fde20b90edf) | 
`public float `[`_ax`](#structnetwork_1_1datatrans_1a31dae8ec2e7a0ce2f74d619beba0cd01) | 
`public float `[`_ay`](#structnetwork_1_1datatrans_1abb975595ed67f620637f05124fcde4db) | 
`public inline  `[`datatrans`](#structnetwork_1_1datatrans_1aeb13735d17f9bf42ab5ea3e82180832e)`(Command code,size_t id,int type,float x,float y,float zx,float zy,float ax,float ay)` | Construct a new data do be transfered.
`public inline  `[`~datatrans`](#structnetwork_1_1datatrans_1ae6631d5a5cf2242511c3bde302ecc86f)`()` | 
`public template<>`  <br/>`inline void `[`serialize`](#structnetwork_1_1datatrans_1a7a134acb0f0e8ac85c90cbaaa378da86)`(Archive & ar,const unsigned int version)` | serialize methode for serialization

## Members

#### `public Command `[`_code`](#structnetwork_1_1datatrans_1a865a2e39d7e0f5e5769eb80fd9373283) 

#### `public size_t `[`_id`](#structnetwork_1_1datatrans_1adc842714ffc3ff39f768852a5c4e0069) 

#### `public int `[`_type`](#structnetwork_1_1datatrans_1a17c6e797b84c1f1dfee162e0ac3cd9f7) 

#### `public float `[`_x`](#structnetwork_1_1datatrans_1a39c96eb7ca7054b7740f44783745a478) 

#### `public float `[`_y`](#structnetwork_1_1datatrans_1a62b0f538e286134bec7e4b91d6bf8e19) 

#### `public float `[`_zx`](#structnetwork_1_1datatrans_1aa16efafd5c445b558e610d87c90eadd8) 

#### `public float `[`_zy`](#structnetwork_1_1datatrans_1a8a80b19467290e100a5d7fde20b90edf) 

#### `public float `[`_ax`](#structnetwork_1_1datatrans_1a31dae8ec2e7a0ce2f74d619beba0cd01) 

#### `public float `[`_ay`](#structnetwork_1_1datatrans_1abb975595ed67f620637f05124fcde4db) 

#### `public inline  `[`datatrans`](#structnetwork_1_1datatrans_1aeb13735d17f9bf42ab5ea3e82180832e)`(Command code,size_t id,int type,float x,float y,float zx,float zy,float ax,float ay)` 

Construct a new data do be transfered.

#### Parameters
* `code` 

* `id` 

* `type` 

* `x` 

* `y` 

* `zx` 

* `zy` 

* `ax` 

* `ay`

#### `public inline  `[`~datatrans`](#structnetwork_1_1datatrans_1ae6631d5a5cf2242511c3bde302ecc86f)`()` 

#### `public template<>`  <br/>`inline void `[`serialize`](#structnetwork_1_1datatrans_1a7a134acb0f0e8ac85c90cbaaa378da86)`(Archive & ar,const unsigned int version)` 

serialize methode for serialization

#### Parameters
* `Archive` 

#### Parameters
* `ar` 

* `version`

# namespace `rtype` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`enum `[`SceneName`](#Scene_8hpp_1ad80375e169e619db7ebc6377d1679287)            | 
`public void `[`changeSceneAction`](#EventActions_8hpp_1a9e47801601bea86424f336c86faea480)`(`[`registry`](#classregistry)` &,std::shared_ptr< `[`IScene`](#classrtype_1_1IScene)` >,std::shared_ptr< `[`IScene`](#classrtype_1_1IScene)` >)`            | 
`class `[`rtype::ClientCore`](#classrtype_1_1ClientCore) | 
`class `[`rtype::IScene`](#classrtype_1_1IScene) | 
`class `[`rtype::Scene`](#classrtype_1_1Scene) | 
`class `[`rtype::ServerCore`](#classrtype_1_1ServerCore) | 

## Members

#### `enum `[`SceneName`](#Scene_8hpp_1ad80375e169e619db7ebc6377d1679287) 

 Values                         | Descriptions                                
--------------------------------|---------------------------------------------
Cinematic            | 
Loading            | 
MainMenu            | 
Transition            | 
Settings            | 
Credits            | 
NameInsertion            | 
VesselChoice            | 
RoomChoice            | 
RoomLoading            | 
Game            | 

#### `public void `[`changeSceneAction`](#EventActions_8hpp_1a9e47801601bea86424f336c86faea480)`(`[`registry`](#classregistry)` &,std::shared_ptr< `[`IScene`](#classrtype_1_1IScene)` >,std::shared_ptr< `[`IScene`](#classrtype_1_1IScene)` >)` 

# class `rtype::ClientCore` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public  `[`ClientCore`](#classrtype_1_1ClientCore_1a2ffbf27fe3590bd37813876f9f00c5ca)`(std::string,int)` | 
`public  `[`~ClientCore`](#classrtype_1_1ClientCore_1a0a625106e6afc8ae2c18f2fe3e00e2b9)`()` | 
`public void `[`set_components`](#classrtype_1_1ClientCore_1a47a38945daee87130f29115360cbd574)`()` | 
`public void `[`set_events_systems`](#classrtype_1_1ClientCore_1ab7471600ffb7a773adc8d44344e66ae1)`()` | 
`public void `[`set_systems`](#classrtype_1_1ClientCore_1a9b3b6fd02986f1b142edc4f8410afe74)`()` | 
`public void `[`run`](#classrtype_1_1ClientCore_1a6e12a2ea31abac408ca6b912e9886668)`()` | 
`public void `[`createMainMenu`](#classrtype_1_1ClientCore_1a518f9326c77f92f3476cac22390c8016)`()` | 
`public void `[`createRoomLoading`](#classrtype_1_1ClientCore_1a1fda01a2a59a76cdcbd4dde1bd892991)`()` | 
`public void `[`createGame`](#classrtype_1_1ClientCore_1a868a22a3a870bfad516ee2219a2f2c1f)`()` | 

## Members

#### `public  `[`ClientCore`](#classrtype_1_1ClientCore_1a2ffbf27fe3590bd37813876f9f00c5ca)`(std::string,int)` 

#### `public  `[`~ClientCore`](#classrtype_1_1ClientCore_1a0a625106e6afc8ae2c18f2fe3e00e2b9)`()` 

#### `public void `[`set_components`](#classrtype_1_1ClientCore_1a47a38945daee87130f29115360cbd574)`()` 

#### `public void `[`set_events_systems`](#classrtype_1_1ClientCore_1ab7471600ffb7a773adc8d44344e66ae1)`()` 

#### `public void `[`set_systems`](#classrtype_1_1ClientCore_1a9b3b6fd02986f1b142edc4f8410afe74)`()` 

#### `public void `[`run`](#classrtype_1_1ClientCore_1a6e12a2ea31abac408ca6b912e9886668)`()` 

#### `public void `[`createMainMenu`](#classrtype_1_1ClientCore_1a518f9326c77f92f3476cac22390c8016)`()` 

#### `public void `[`createRoomLoading`](#classrtype_1_1ClientCore_1a1fda01a2a59a76cdcbd4dde1bd892991)`()` 

#### `public void `[`createGame`](#classrtype_1_1ClientCore_1a868a22a3a870bfad516ee2219a2f2c1f)`()` 

# class `rtype::IScene` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public inline  `[`IScene`](#classrtype_1_1IScene_1a4d7f11be2a58aa0fe3f1284cbb06c50a)`()` | 
`public inline  `[`~IScene`](#classrtype_1_1IScene_1ac5bef1212a82eaa65ef765dc9c9b0687)`()` | 
`public void `[`addEntity`](#classrtype_1_1IScene_1a607f06da39e0325a77dd17646b2ed588)`(`[`entity`](#classentity)`)` | 
`public void `[`setActivity`](#classrtype_1_1IScene_1a84f0622d635943591d57720e2667c8ec)`(`[`registry`](#classregistry)` &,bool)` | 
`protected std::vector< `[`entity`](#classentity)` > `[`_entities`](#classrtype_1_1IScene_1a744e1d1ae75bd8418080d531f4de46e8) | 

## Members

#### `public inline  `[`IScene`](#classrtype_1_1IScene_1a4d7f11be2a58aa0fe3f1284cbb06c50a)`()` 

#### `public inline  `[`~IScene`](#classrtype_1_1IScene_1ac5bef1212a82eaa65ef765dc9c9b0687)`()` 

#### `public void `[`addEntity`](#classrtype_1_1IScene_1a607f06da39e0325a77dd17646b2ed588)`(`[`entity`](#classentity)`)` 

#### `public void `[`setActivity`](#classrtype_1_1IScene_1a84f0622d635943591d57720e2667c8ec)`(`[`registry`](#classregistry)` &,bool)` 

#### `protected std::vector< `[`entity`](#classentity)` > `[`_entities`](#classrtype_1_1IScene_1a744e1d1ae75bd8418080d531f4de46e8) 

# class `rtype::Scene` 

```
class rtype::Scene
  : public rtype::IScene
```  

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public  `[`Scene`](#classrtype_1_1Scene_1a5729f02ff001ceed6598748260404ba3)`()` | 
`public  `[`~Scene`](#classrtype_1_1Scene_1aa050da328cdf89405306e6a57a2d9855)`()` | 
`public virtual void `[`addEntity`](#classrtype_1_1Scene_1a2af1d66869fac1b3e35711bac99faa98)`(`[`entity`](#classentity)`)` | 
`public virtual void `[`setActivity`](#classrtype_1_1Scene_1acabfaa7057e8950b23b8f9d89c3ae586)`(`[`registry`](#classregistry)` &,bool)` | 

## Members

#### `public  `[`Scene`](#classrtype_1_1Scene_1a5729f02ff001ceed6598748260404ba3)`()` 

#### `public  `[`~Scene`](#classrtype_1_1Scene_1aa050da328cdf89405306e6a57a2d9855)`()` 

#### `public virtual void `[`addEntity`](#classrtype_1_1Scene_1a2af1d66869fac1b3e35711bac99faa98)`(`[`entity`](#classentity)`)` 

#### `public virtual void `[`setActivity`](#classrtype_1_1Scene_1acabfaa7057e8950b23b8f9d89c3ae586)`(`[`registry`](#classregistry)` &,bool)` 

# class `rtype::ServerCore` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public  `[`ServerCore`](#classrtype_1_1ServerCore_1ad575456755c9dbb49046d229addfe0d0)`(int port)` | 
`public  `[`~ServerCore`](#classrtype_1_1ServerCore_1a6d2e1e92a18212e9e37a5532e8bef3fe)`()` | 
`public void `[`set_components`](#classrtype_1_1ServerCore_1a251eab798799d4f70f2862fd4c090369)`()` | 
`public void `[`set_systems`](#classrtype_1_1ServerCore_1a98db4db19fc67bd57e818dc40bb5ebdf)`()` | 
`public void `[`run`](#classrtype_1_1ServerCore_1a2cb96c43289cb8c9715281d734448ead)`()` | 

## Members

#### `public  `[`ServerCore`](#classrtype_1_1ServerCore_1ad575456755c9dbb49046d229addfe0d0)`(int port)` 

#### `public  `[`~ServerCore`](#classrtype_1_1ServerCore_1a6d2e1e92a18212e9e37a5532e8bef3fe)`()` 

#### `public void `[`set_components`](#classrtype_1_1ServerCore_1a251eab798799d4f70f2862fd4c090369)`()` 

#### `public void `[`set_systems`](#classrtype_1_1ServerCore_1a98db4db19fc67bd57e818dc40bb5ebdf)`()` 

#### `public void `[`run`](#classrtype_1_1ServerCore_1a2cb96c43289cb8c9715281d734448ead)`()` 

# namespace `Systems` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public void `[`position_system`](#R-typeClient_2includes_2Systems_8hpp_1ac8264cacfff67c96f253114b4b801fc0)`(`[`registry`](#classregistry)` & reg,`[`sparse_array`](#classsparse__array)`< component::activity > &,`[`sparse_array](#classsparse__array)< [component::velocity`](#structcomponent_1_1velocity)` > &,`[`sparse_array](#classsparse__array)< [component::position`](#structcomponent_1_1position)` > &)`            | 
`public void `[`anim_system`](#R-typeClient_2includes_2Systems_8hpp_1acc60081e072b9257d7730f88770a8609)`(`[`registry`](#classregistry)` & reg,`[`sparse_array`](#classsparse__array)`< component::activity > &,`[`sparse_array](#classsparse__array)< [component::drawable`](#structcomponent_1_1drawable)` > &)`            | 
`public void `[`scrolling_system`](#R-typeClient_2includes_2Systems_8hpp_1a1cf77b5b7e665eda8e91c7b3cdb0895a)`(`[`registry`](#classregistry)` & reg,`[`sparse_array`](#classsparse__array)`< component::activity > &,`[`sparse_array](#classsparse__array)< [component::scrolling`](#structcomponent_1_1scrolling)` > &,`[`sparse_array](#classsparse__array)< [component::position`](#structcomponent_1_1position)` > &)`            | 
`public void `[`position_system`](#R-typeServer_2includes_2Systems_8hpp_1a68d57904e1069bd531327c6b68d66ac1)`(`[`registry`](#classregistry)` & reg,`[`sparse_array](#classsparse__array)< [component::velocity`](#structcomponent_1_1velocity)` > &,`[`sparse_array](#classsparse__array)< [component::position`](#structcomponent_1_1position)` > &)`            | 
`class `[`Systems::clickable`](#classSystems_1_1clickable) | 
`class `[`Systems::drawable`](#classSystems_1_1drawable) | 
`class `[`Systems::gameplay`](#classSystems_1_1gameplay) | 
`class `[`Systems::manage_requests`](#classSystems_1_1manage__requests) | 
`class `[`Systems::sound`](#classSystems_1_1sound) | 

## Members

#### `public void `[`position_system`](#R-typeClient_2includes_2Systems_8hpp_1ac8264cacfff67c96f253114b4b801fc0)`(`[`registry`](#classregistry)` & reg,`[`sparse_array`](#classsparse__array)`< component::activity > &,`[`sparse_array](#classsparse__array)< [component::velocity`](#structcomponent_1_1velocity)` > &,`[`sparse_array](#classsparse__array)< [component::position`](#structcomponent_1_1position)` > &)` 

#### `public void `[`anim_system`](#R-typeClient_2includes_2Systems_8hpp_1acc60081e072b9257d7730f88770a8609)`(`[`registry`](#classregistry)` & reg,`[`sparse_array`](#classsparse__array)`< component::activity > &,`[`sparse_array](#classsparse__array)< [component::drawable`](#structcomponent_1_1drawable)` > &)` 

#### `public void `[`scrolling_system`](#R-typeClient_2includes_2Systems_8hpp_1a1cf77b5b7e665eda8e91c7b3cdb0895a)`(`[`registry`](#classregistry)` & reg,`[`sparse_array`](#classsparse__array)`< component::activity > &,`[`sparse_array](#classsparse__array)< [component::scrolling`](#structcomponent_1_1scrolling)` > &,`[`sparse_array](#classsparse__array)< [component::position`](#structcomponent_1_1position)` > &)` 

#### `public void `[`position_system`](#R-typeServer_2includes_2Systems_8hpp_1a68d57904e1069bd531327c6b68d66ac1)`(`[`registry`](#classregistry)` & reg,`[`sparse_array](#classsparse__array)< [component::velocity`](#structcomponent_1_1velocity)` > &,`[`sparse_array](#classsparse__array)< [component::position`](#structcomponent_1_1position)` > &)` 

# class `Systems::clickable` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public inline  `[`clickable`](#classSystems_1_1clickable_1a78e99dc0a07b93dab6614ac2985aded3)`(std::shared_ptr< `[`graphics::IDisplay`](#classgraphics_1_1IDisplay)` > disp)` | 
`public inline  `[`~clickable`](#classSystems_1_1clickable_1a437ca96d73c058c9a1c9b88ee986a62b)`()` | 
`public void `[`operator()`](#classSystems_1_1clickable_1a9a04b819dffe4fbaf292a3eb42588bd5)`(`[`registry`](#classregistry)` & reg,`[`sparse_array`](#classsparse__array)`< component::activity > &,`[`sparse_array](#classsparse__array)< [component::drawable`](#structcomponent_1_1drawable)` > & c,`[`sparse_array](#classsparse__array)< [component::clickable`](#structcomponent_1_1clickable)` > &,`[`sparse_array](#classsparse__array)< [component::position`](#structcomponent_1_1position)` > &) const` | 

## Members

#### `public inline  `[`clickable`](#classSystems_1_1clickable_1a78e99dc0a07b93dab6614ac2985aded3)`(std::shared_ptr< `[`graphics::IDisplay`](#classgraphics_1_1IDisplay)` > disp)` 

#### `public inline  `[`~clickable`](#classSystems_1_1clickable_1a437ca96d73c058c9a1c9b88ee986a62b)`()` 

#### `public void `[`operator()`](#classSystems_1_1clickable_1a9a04b819dffe4fbaf292a3eb42588bd5)`(`[`registry`](#classregistry)` & reg,`[`sparse_array`](#classsparse__array)`< component::activity > &,`[`sparse_array](#classsparse__array)< [component::drawable`](#structcomponent_1_1drawable)` > & c,`[`sparse_array](#classsparse__array)< [component::clickable`](#structcomponent_1_1clickable)` > &,`[`sparse_array](#classsparse__array)< [component::position`](#structcomponent_1_1position)` > &) const` 

# class `Systems::drawable` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public inline  `[`drawable`](#classSystems_1_1drawable_1aa244715ada28d393864a0b9eed835765)`(std::shared_ptr< `[`graphics::IDisplay`](#classgraphics_1_1IDisplay)` > disp)` | 
`public inline  `[`~drawable`](#classSystems_1_1drawable_1af972280d720c9783eb826fa3f69f96b5)`()` | 
`public void `[`operator()`](#classSystems_1_1drawable_1a1028ec504f501ee8d0c291a355f465a9)`(`[`registry`](#classregistry)` &,`[`sparse_array`](#classsparse__array)`< component::activity > &,`[`sparse_array](#classsparse__array)< [component::position`](#structcomponent_1_1position)` > &,`[`sparse_array](#classsparse__array)< [component::drawable`](#structcomponent_1_1drawable)` > &) const` | 

## Members

#### `public inline  `[`drawable`](#classSystems_1_1drawable_1aa244715ada28d393864a0b9eed835765)`(std::shared_ptr< `[`graphics::IDisplay`](#classgraphics_1_1IDisplay)` > disp)` 

#### `public inline  `[`~drawable`](#classSystems_1_1drawable_1af972280d720c9783eb826fa3f69f96b5)`()` 

#### `public void `[`operator()`](#classSystems_1_1drawable_1a1028ec504f501ee8d0c291a355f465a9)`(`[`registry`](#classregistry)` &,`[`sparse_array`](#classsparse__array)`< component::activity > &,`[`sparse_array](#classsparse__array)< [component::position`](#structcomponent_1_1position)` > &,`[`sparse_array](#classsparse__array)< [component::drawable`](#structcomponent_1_1drawable)` > &) const` 

# class `Systems::gameplay` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public inline  `[`gameplay`](#classSystems_1_1gameplay_1a4bf6e0b9f467b49448bdb8cc14bb6f0d)`(std::shared_ptr< `[`network::INetworker`](#classnetwork_1_1INetworker)` > net)` | 
`public inline  `[`~gameplay`](#classSystems_1_1gameplay_1a901ee3199948e96b84c42cb75af2c122)`()` | 
`public void `[`operator()`](#classSystems_1_1gameplay_1aba5b8d8c52d35ce41fb4658a6121b03a)`(`[`registry`](#classregistry)` & reg) const` | 
`public void `[`update_room`](#classSystems_1_1gameplay_1a968b77a92eefc4dbb48c4d99dfb0e7b1)`(`[`registry`](#classregistry)` &,size_t)` | 

## Members

#### `public inline  `[`gameplay`](#classSystems_1_1gameplay_1a4bf6e0b9f467b49448bdb8cc14bb6f0d)`(std::shared_ptr< `[`network::INetworker`](#classnetwork_1_1INetworker)` > net)` 

#### `public inline  `[`~gameplay`](#classSystems_1_1gameplay_1a901ee3199948e96b84c42cb75af2c122)`()` 

#### `public void `[`operator()`](#classSystems_1_1gameplay_1aba5b8d8c52d35ce41fb4658a6121b03a)`(`[`registry`](#classregistry)` & reg) const` 

#### `public void `[`update_room`](#classSystems_1_1gameplay_1a968b77a92eefc4dbb48c4d99dfb0e7b1)`(`[`registry`](#classregistry)` &,size_t)` 

# class `Systems::manage_requests` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public void `[`update`](#classSystems_1_1manage__requests_1a693758179cab4bdaf785bd1df7c0d069)`(`[`registry`](#classregistry)` &,`[`network::datatrans`](#structnetwork_1_1datatrans)` &) const` | 
`public inline  `[`manage_requests`](#classSystems_1_1manage__requests_1ad3f370848f59c4c7500e109f2579b083)`(std::shared_ptr< `[`network::INetworker`](#classnetwork_1_1INetworker)` > net)` | 
`public inline  `[`~manage_requests`](#classSystems_1_1manage__requests_1a784761fea78586884096aabe7dea46f0)`()` | 
`public void `[`operator()`](#classSystems_1_1manage__requests_1a82d4e9918f725f8bff2a36062163c262)`(`[`registry`](#classregistry)` & reg) const` | 

## Members

#### `public void `[`update`](#classSystems_1_1manage__requests_1a693758179cab4bdaf785bd1df7c0d069)`(`[`registry`](#classregistry)` &,`[`network::datatrans`](#structnetwork_1_1datatrans)` &) const` 

#### `public inline  `[`manage_requests`](#classSystems_1_1manage__requests_1ad3f370848f59c4c7500e109f2579b083)`(std::shared_ptr< `[`network::INetworker`](#classnetwork_1_1INetworker)` > net)` 

#### `public inline  `[`~manage_requests`](#classSystems_1_1manage__requests_1a784761fea78586884096aabe7dea46f0)`()` 

#### `public void `[`operator()`](#classSystems_1_1manage__requests_1a82d4e9918f725f8bff2a36062163c262)`(`[`registry`](#classregistry)` & reg) const` 

# class `Systems::sound` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public inline  `[`sound`](#classSystems_1_1sound_1a22b6be2f018bbbce04b4de034b0c2145)`(std::shared_ptr< `[`graphics::IDisplay`](#classgraphics_1_1IDisplay)` > disp)` | 
`public inline  `[`~sound`](#classSystems_1_1sound_1ae4f2d1e54cebef9ee7ba82e2895ebc3e)`()` | 
`public void `[`operator()`](#classSystems_1_1sound_1ac5d0e2f248d57c89a7e55c3c9fb6a508)`(`[`registry`](#classregistry)` &,`[`sparse_array`](#classsparse__array)`< component::activity > &,`[`sparse_array](#classsparse__array)< [component::sound`](#structcomponent_1_1sound)` > &) const` | 

## Members

#### `public inline  `[`sound`](#classSystems_1_1sound_1a22b6be2f018bbbce04b4de034b0c2145)`(std::shared_ptr< `[`graphics::IDisplay`](#classgraphics_1_1IDisplay)` > disp)` 

#### `public inline  `[`~sound`](#classSystems_1_1sound_1ae4f2d1e54cebef9ee7ba82e2895ebc3e)`()` 

#### `public void `[`operator()`](#classSystems_1_1sound_1ac5d0e2f248d57c89a7e55c3c9fb6a508)`(`[`registry`](#classregistry)` &,`[`sparse_array`](#classsparse__array)`< component::activity > &,`[`sparse_array](#classsparse__array)< [component::sound`](#structcomponent_1_1sound)` > &) const` 

# class `ClockTime` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public inline  `[`ClockTime`](#classClockTime_1a6ace7b63b14cda5e085fba1a043b05ce)`()` | 
`public inline  `[`~ClockTime`](#classClockTime_1ac308325b87407eb91279113add6675e7)`()` | 
`public inline bool `[`launched`](#classClockTime_1a3debc6cc818f7844b2b13ef051ac8c18)`()` | 
`public inline void `[`launchChrono`](#classClockTime_1af3b7a20b4bdcfd8a867bb04e13a84159)`()` | 
`public inline void `[`reset`](#classClockTime_1abf52ec1d8c74c1ea8f284fb28c2ad159)`()` | 
`public template<>`  <br/>`inline T `[`getElapsedTime`](#classClockTime_1a1b3752b75c54315d023c0e4d84963c21)`()` | 

## Members

#### `public inline  `[`ClockTime`](#classClockTime_1a6ace7b63b14cda5e085fba1a043b05ce)`()` 

#### `public inline  `[`~ClockTime`](#classClockTime_1ac308325b87407eb91279113add6675e7)`()` 

#### `public inline bool `[`launched`](#classClockTime_1a3debc6cc818f7844b2b13ef051ac8c18)`()` 

#### `public inline void `[`launchChrono`](#classClockTime_1af3b7a20b4bdcfd8a867bb04e13a84159)`()` 

#### `public inline void `[`reset`](#classClockTime_1abf52ec1d8c74c1ea8f284fb28c2ad159)`()` 

#### `public template<>`  <br/>`inline T `[`getElapsedTime`](#classClockTime_1a1b3752b75c54315d023c0e4d84963c21)`()` 

# class `DLLoader` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public inline  `[`DLLoader`](#classDLLoader_1acc5f868150527e09aa8a6aaac63666d6)`(std::string path)` | 
`public inline  `[`~DLLoader`](#classDLLoader_1aea867b497cf92c50f85ad7e1d37962ae)`()` | 
`public inline void `[`check_dlerror`](#classDLLoader_1a8922cc5d294e7f0ac39a3ad6ebd85d47)`()` | 
`public template<>`  <br/>`inline std::shared_ptr< T > `[`getInstance`](#classDLLoader_1a17bb9331de1df5b07a227f85b6072955)`(std::string sym,Types &&... va)` | 

## Members

#### `public inline  `[`DLLoader`](#classDLLoader_1acc5f868150527e09aa8a6aaac63666d6)`(std::string path)` 

#### `public inline  `[`~DLLoader`](#classDLLoader_1aea867b497cf92c50f85ad7e1d37962ae)`()` 

#### `public inline void `[`check_dlerror`](#classDLLoader_1a8922cc5d294e7f0ac39a3ad6ebd85d47)`()` 

#### `public template<>`  <br/>`inline std::shared_ptr< T > `[`getInstance`](#classDLLoader_1a17bb9331de1df5b07a227f85b6072955)`(std::string sym,Types &&... va)` 

# class `Enet` 

```
class Enet
  : public network::INetworker
```  

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public  `[`Enet`](#classEnet_1a24b6b0b666d3cab4103879cdecd06f17)`(int port)` | 
`public  `[`Enet`](#classEnet_1a3b9a358ac7368633daa2eaa00f177540)`(std::string ip,int port)` | 
`public  `[`~Enet`](#classEnet_1a1c08ab8ef4e0a2b4f6e774d656130f44)`()` | 
`public virtual void `[`send_data`](#classEnet_1a105ab2b31e06bcc320e4ba1b7c7373b4)`()` | Send data to connected peer.
`public virtual int `[`receive_data`](#classEnet_1ab85cb2a871b7095762f4b8571c761a01)`(int timeout)` | Get data that any peer sent.
`public void `[`broadcast`](#classEnet_1af70c11f3b3d8496c2e95d0561b54cc2c)`(ENetPeer * peer,void * data)` | 
`public ENetEvent `[`get_event`](#classEnet_1aaa8cb37747b47c53c23a50334f7cc655)`()` | 
`public void `[`reset_peer`](#classEnet_1a1ba15484142587c32aa29aeef41027d5)`()` | 

## Members

#### `public  `[`Enet`](#classEnet_1a24b6b0b666d3cab4103879cdecd06f17)`(int port)` 

#### `public  `[`Enet`](#classEnet_1a3b9a358ac7368633daa2eaa00f177540)`(std::string ip,int port)` 

#### `public  `[`~Enet`](#classEnet_1a1c08ab8ef4e0a2b4f6e774d656130f44)`()` 

#### `public virtual void `[`send_data`](#classEnet_1a105ab2b31e06bcc320e4ba1b7c7373b4)`()` 

Send data to connected peer.

#### Parameters
* `data` Data to send

#### `public virtual int `[`receive_data`](#classEnet_1ab85cb2a871b7095762f4b8571c761a01)`(int timeout)` 

Get data that any peer sent.

#### Parameters
* `timeout` time to wait

#### Returns
void* Received data

#### `public void `[`broadcast`](#classEnet_1af70c11f3b3d8496c2e95d0561b54cc2c)`(ENetPeer * peer,void * data)` 

#### `public ENetEvent `[`get_event`](#classEnet_1aaa8cb37747b47c53c23a50334f7cc655)`()` 

#### `public void `[`reset_peer`](#classEnet_1a1ba15484142587c32aa29aeef41027d5)`()` 

# class `entity` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public std::size_t `[`id`](#classentity_1a7995f0bfb6e947efb47c96ecfe3bb8ff) | 
`public inline  explicit `[`entity`](#classentity_1a7cfd8e1d10076bc4139e8b86cd2897b1)`(std::size_t _id)` | 
`public inline  `[`~entity`](#classentity_1acec2b315e0eddb40f6c2dc1a7688293e)`()` | 
`public inline  `[`operator size_t`](#classentity_1a5fcb6528bfcdf84ac69440ae83720b02)`() const` | 

## Members

#### `public std::size_t `[`id`](#classentity_1a7995f0bfb6e947efb47c96ecfe3bb8ff) 

#### `public inline  explicit `[`entity`](#classentity_1a7cfd8e1d10076bc4139e8b86cd2897b1)`(std::size_t _id)` 

#### `public inline  `[`~entity`](#classentity_1acec2b315e0eddb40f6c2dc1a7688293e)`()` 

#### `public inline  `[`operator size_t`](#classentity_1a5fcb6528bfcdf84ac69440ae83720b02)`() const` 

# class `registry::entity_manager_t` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public inline  `[`entity_manager_t`](#classregistry_1_1entity__manager__t_1a6cfdd1c6b4c2efaa442c8557b451fa65)`(`[`registry`](#classregistry)` & reg)` | 
`public inline  `[`~entity_manager_t`](#classregistry_1_1entity__manager__t_1a68eeaf0849307b54d7d423bf0080e0ec)`()` | 
`public inline `[`entity_t`](#classentity)` `[`spawn_entity`](#classregistry_1_1entity__manager__t_1a18c45131a69854ecde5b2e08cffc5868)`()` | 
`public inline `[`entity_t`](#classentity)` `[`entity_from_index`](#classregistry_1_1entity__manager__t_1a1f73a165e15d3c8471f0252ce7e694ac)`(std::size_t idx)` | 
`public inline void `[`kill_entity`](#classregistry_1_1entity__manager__t_1af11740fa56d974822089dbdef83c0c7b)`(`[`entity_t`](#classentity)` const & e)` | 
`public template<>`  <br/>`inline `[`sparse_array`](#classsparse__array)`< Component >::reference_type `[`add_component`](#classregistry_1_1entity__manager__t_1ad15a3b14b1047762e590067c1dbc01ea)`(`[`entity_t`](#classentity)` const & to,Component & c)` | 
`public template<>`  <br/>`inline `[`sparse_array`](#classsparse__array)`< Component >::reference_type `[`add_component`](#classregistry_1_1entity__manager__t_1a865c29695ff75f43064af3b76076e095)`(`[`entity_t`](#classentity)` const & to,Component && c)` | 
`public template<>`  <br/>`inline `[`sparse_array`](#classsparse__array)`< Component >::reference_type `[`emplace_component`](#classregistry_1_1entity__manager__t_1ab7590ac45186bafa3bd77e247d3a3259)`(`[`entity_t`](#classentity)` const & to,Params &&... p)` | 
`public template<>`  <br/>`inline void `[`remove_component`](#classregistry_1_1entity__manager__t_1aec983d6a81f431c0701026fa1c17cbbc)`(`[`entity_t`](#classentity)` const & from)` | 

## Members

#### `public inline  `[`entity_manager_t`](#classregistry_1_1entity__manager__t_1a6cfdd1c6b4c2efaa442c8557b451fa65)`(`[`registry`](#classregistry)` & reg)` 

#### `public inline  `[`~entity_manager_t`](#classregistry_1_1entity__manager__t_1a68eeaf0849307b54d7d423bf0080e0ec)`()` 

#### `public inline `[`entity_t`](#classentity)` `[`spawn_entity`](#classregistry_1_1entity__manager__t_1a18c45131a69854ecde5b2e08cffc5868)`()` 

#### `public inline `[`entity_t`](#classentity)` `[`entity_from_index`](#classregistry_1_1entity__manager__t_1a1f73a165e15d3c8471f0252ce7e694ac)`(std::size_t idx)` 

#### `public inline void `[`kill_entity`](#classregistry_1_1entity__manager__t_1af11740fa56d974822089dbdef83c0c7b)`(`[`entity_t`](#classentity)` const & e)` 

#### `public template<>`  <br/>`inline `[`sparse_array`](#classsparse__array)`< Component >::reference_type `[`add_component`](#classregistry_1_1entity__manager__t_1ad15a3b14b1047762e590067c1dbc01ea)`(`[`entity_t`](#classentity)` const & to,Component & c)` 

#### `public template<>`  <br/>`inline `[`sparse_array`](#classsparse__array)`< Component >::reference_type `[`add_component`](#classregistry_1_1entity__manager__t_1a865c29695ff75f43064af3b76076e095)`(`[`entity_t`](#classentity)` const & to,Component && c)` 

#### `public template<>`  <br/>`inline `[`sparse_array`](#classsparse__array)`< Component >::reference_type `[`emplace_component`](#classregistry_1_1entity__manager__t_1ab7590ac45186bafa3bd77e247d3a3259)`(`[`entity_t`](#classentity)` const & to,Params &&... p)` 

#### `public template<>`  <br/>`inline void `[`remove_component`](#classregistry_1_1entity__manager__t_1aec983d6a81f431c0701026fa1c17cbbc)`(`[`entity_t`](#classentity)` const & from)` 

# class `Error` 

```
class Error
  : public exception
```  

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public inline  `[`Error`](#classError_1a531664ff4c9e228a269aea757d23236f)`(std::string message)` | 
`public inline  `[`~Error`](#classError_1a1a45d42a3a035d510333cdfeb36a0e93)`()` | 
`public inline const char * `[`what`](#classError_1aba98fd2392ef0a6ac88623dfdca15102)`() const` | 

## Members

#### `public inline  `[`Error`](#classError_1a531664ff4c9e228a269aea757d23236f)`(std::string message)` 

#### `public inline  `[`~Error`](#classError_1a1a45d42a3a035d510333cdfeb36a0e93)`()` 

#### `public inline const char * `[`what`](#classError_1aba98fd2392ef0a6ac88623dfdca15102)`() const` 

# class `Raylib` 

```
class Raylib
  : public graphics::IDisplay
```  

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public  `[`Raylib`](#classRaylib_1a6912339ce0a1c189a7b756ad3ca1fe50)`()` | Construct a new [Raylib](#classRaylib):: [Raylib](#classRaylib) object.
`public  `[`~Raylib`](#classRaylib_1a73c8b0f22704986442fd4d63146ac0a7)`()` | Destroy the [Raylib](#classRaylib):: [Raylib](#classRaylib) object.
`public virtual void `[`openWin`](#classRaylib_1a6817466000222151e6dea205ba5d44e6)`()` | Open a window.
`public virtual int `[`getScreenWidth`](#classRaylib_1ab07e6a62d1031b183c9cf894ee1a5f3a)`()` | Get the window width.
`public virtual int `[`getScreenHeight`](#classRaylib_1af0fd264584fc278602d28188cfc04123)`()` | Get the window Height.
`public virtual void `[`setFps`](#classRaylib_1a5102ca76dfb9e5dd2b3dd2bfbda3a04d)`(int fps)` | Set frame rate.
`public virtual bool `[`isOpen`](#classRaylib_1a72c614e50e0ba7cc2994f7b4c9a2e3b5)`()` | Verify if the window is open.
`public virtual void `[`closeWin`](#classRaylib_1a553668e178d1a09c176293f2e3210ead)`()` | Close window.
`public virtual bool `[`pollEvent`](#classRaylib_1a70c7f9c8a078818a737a796d21594c5f)`()` | Verify if an event happened.
`public virtual void `[`beginDrawing`](#classRaylib_1ae2f46bc478414d002510e8268fc94107)`()` | Start drawing This function must be called before drawing anything.
`public virtual void `[`clearBackground`](#classRaylib_1a452fd23d2d7412fb4a3035c7337f28f2)`()` | Clear background.
`public virtual void `[`draw`](#classRaylib_1ab24a2afc51a35fe0cd8d99632d82b144)`(`[`component::position`](#structcomponent_1_1position)` posComp,`[`component::drawable`](#structcomponent_1_1drawable)` drawComp)` | Draw entities.
`public virtual void `[`endDrawing`](#classRaylib_1a247b79289042dffcbaa45eaa90e1a9c4)`()` | End drawing This function must be called to stop drawing.
`public virtual bool `[`isKeyPressed`](#classRaylib_1ae89ed6e0dc80c915e007b85ddb9e257e)`(Keyboard key)` | verify if a keyboard touch was pressed once
`public virtual bool `[`isKeyBeingPressed`](#classRaylib_1abdd2681427e02f7c2a4a24ff8325bb6c)`(Keyboard key)` | verify if a keyboard touch is been pressed
`public virtual bool `[`isKeyReleased`](#classRaylib_1af01e7b95d67a38b65665fe0596c6ece2)`(Keyboard key)` | verify if a keyboard touch was released once
`public virtual bool `[`isMouseButtonPressed`](#classRaylib_1af47b4c4b37a12d11942f5492f8863446)`(graphics::MouseButton button)` | 
`public virtual bool `[`isMouseButtonBeingPressed`](#classRaylib_1a1cd45d48b839a21ad0b75063a893847f)`(graphics::MouseButton button)` | 
`public virtual bool `[`isMouseButtonReleased`](#classRaylib_1a4144ebbc3754a4807d623ca1ffb9681f)`(graphics::MouseButton button)` | 
`public virtual `[`Vector2D`](#structVector2D)`< float > `[`getMousePosition`](#classRaylib_1a62b1e9caf4cbe2ee8864c2c72dcdea88)`()` | 
`public virtual void `[`playSound`](#classRaylib_1a53b5cea12a2daead5e9a3bc7728944c5)`(std::string path,bool looping)` | 
`public virtual void `[`stopSound`](#classRaylib_1a3371e3aac7fad1373bf459ccde1b6211)`(std::string path)` | 

## Members

#### `public  `[`Raylib`](#classRaylib_1a6912339ce0a1c189a7b756ad3ca1fe50)`()` 

Construct a new [Raylib](#classRaylib):: [Raylib](#classRaylib) object.

#### `public  `[`~Raylib`](#classRaylib_1a73c8b0f22704986442fd4d63146ac0a7)`()` 

Destroy the [Raylib](#classRaylib):: [Raylib](#classRaylib) object.

#### `public virtual void `[`openWin`](#classRaylib_1a6817466000222151e6dea205ba5d44e6)`()` 

Open a window.

#### `public virtual int `[`getScreenWidth`](#classRaylib_1ab07e6a62d1031b183c9cf894ee1a5f3a)`()` 

Get the window width.

#### Returns
int

#### `public virtual int `[`getScreenHeight`](#classRaylib_1af0fd264584fc278602d28188cfc04123)`()` 

Get the window Height.

#### Returns
int

#### `public virtual void `[`setFps`](#classRaylib_1a5102ca76dfb9e5dd2b3dd2bfbda3a04d)`(int fps)` 

Set frame rate.

#### Parameters
* `fps` : the value of rate

#### `public virtual bool `[`isOpen`](#classRaylib_1a72c614e50e0ba7cc2994f7b4c9a2e3b5)`()` 

Verify if the window is open.

#### Returns
true if the window is open 

#### Returns
false if the window is close

#### `public virtual void `[`closeWin`](#classRaylib_1a553668e178d1a09c176293f2e3210ead)`()` 

Close window.

#### `public virtual bool `[`pollEvent`](#classRaylib_1a70c7f9c8a078818a737a796d21594c5f)`()` 

Verify if an event happened.

#### Returns
true if an event happened 

#### Returns
false if there is no event happened

#### `public virtual void `[`beginDrawing`](#classRaylib_1ae2f46bc478414d002510e8268fc94107)`()` 

Start drawing This function must be called before drawing anything.

#### `public virtual void `[`clearBackground`](#classRaylib_1a452fd23d2d7412fb4a3035c7337f28f2)`()` 

Clear background.

#### `public virtual void `[`draw`](#classRaylib_1ab24a2afc51a35fe0cd8d99632d82b144)`(`[`component::position`](#structcomponent_1_1position)` posComp,`[`component::drawable`](#structcomponent_1_1drawable)` drawComp)` 

Draw entities.

#### Parameters
* `posComp` : position component of the entity 

* `drawComp` : drawable component of the entity

#### `public virtual void `[`endDrawing`](#classRaylib_1a247b79289042dffcbaa45eaa90e1a9c4)`()` 

End drawing This function must be called to stop drawing.

#### `public virtual bool `[`isKeyPressed`](#classRaylib_1ae89ed6e0dc80c915e007b85ddb9e257e)`(Keyboard key)` 

verify if a keyboard touch was pressed once

#### Parameters
* `key` : the key to check 

#### Returns
true if a keyboard touch was pressed once 

#### Returns
false if a keyboard touch was not pressed once

#### `public virtual bool `[`isKeyBeingPressed`](#classRaylib_1abdd2681427e02f7c2a4a24ff8325bb6c)`(Keyboard key)` 

verify if a keyboard touch is been pressed

#### Parameters
* `key` : the key to check 

#### Returns
true if a keyboard touch is been pressed 

#### Returns
false if a keyboard touch is not been pressed

#### `public virtual bool `[`isKeyReleased`](#classRaylib_1af01e7b95d67a38b65665fe0596c6ece2)`(Keyboard key)` 

verify if a keyboard touch was released once

#### Parameters
* `key` : the key to check 

#### Returns
true if a keyboard touch was released once 

#### Returns
false if a keyboard touch was not released once

#### `public virtual bool `[`isMouseButtonPressed`](#classRaylib_1af47b4c4b37a12d11942f5492f8863446)`(graphics::MouseButton button)` 

#### `public virtual bool `[`isMouseButtonBeingPressed`](#classRaylib_1a1cd45d48b839a21ad0b75063a893847f)`(graphics::MouseButton button)` 

#### `public virtual bool `[`isMouseButtonReleased`](#classRaylib_1a4144ebbc3754a4807d623ca1ffb9681f)`(graphics::MouseButton button)` 

#### `public virtual `[`Vector2D`](#structVector2D)`< float > `[`getMousePosition`](#classRaylib_1a62b1e9caf4cbe2ee8864c2c72dcdea88)`()` 

#### `public virtual void `[`playSound`](#classRaylib_1a53b5cea12a2daead5e9a3bc7728944c5)`(std::string path,bool looping)` 

#### `public virtual void `[`stopSound`](#classRaylib_1a3371e3aac7fad1373bf459ccde1b6211)`(std::string path)` 

# class `registry` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public `[`entity_manager_t`](#classregistry_1_1entity__manager__t)` `[`entity_manager`](#classregistry_1a981a0c96d6eb81e70e595a5d450b558c) | 
`public inline  `[`registry`](#classregistry_1a757883d504ab1bb5a06e0faa8e28664d)`()` | 
`public inline  `[`~registry`](#classregistry_1a5007aa52f3b6809650467604be188acf)`()` | 
`public template<>`  <br/>`inline `[`sparse_array`](#classsparse__array)`< Component > & `[`register_component`](#classregistry_1a19c4f7403bb0f2aa5f3f92f8b982fdb1)`()` | 
`public template<>`  <br/>`inline `[`sparse_array`](#classsparse__array)`< Component > & `[`get_components`](#classregistry_1a99ec6244fa73ca7a6042048230a91e9a)`()` | 
`public template<>`  <br/>`inline `[`sparse_array`](#classsparse__array)`< Component > const  & `[`get_components`](#classregistry_1ae35d18b5d8c07828cc5c55bc94f9f4f8)`() const` | 
`public template<>`  <br/>`inline void `[`add_system`](#classregistry_1af9596641371a7191d44293d13c1f69bf)`(Function && f)` | 
`public template<>`  <br/>`inline void `[`add_system`](#classregistry_1af7f9e3380b7c0c33223ace881609465e)`(Function & f)` | 
`public inline void `[`run_systems`](#classregistry_1a1fda5cc52e611441228f8b1c26302060)`()` | 
`public template<>`  <br/>`inline void `[`add_events_system`](#classregistry_1aad3a53aad49d662703ac8769ad0ad676)`(Function && f)` | 
`public template<>`  <br/>`inline void `[`add_events_system`](#classregistry_1a6673f067ecfc396124759235cd32ebbb)`(Function & f)` | 
`public inline void `[`run_events_systems`](#classregistry_1a842591a93878d83bd717f98b82bea2b3)`()` | 
`typedef `[`entity_t`](#classregistry_1afbd442d3a10f483cd3caab2ded84bca2) | 
`typedef `[`deleter_t`](#classregistry_1add498b246f43a27490a289380209237a) | 
`typedef `[`systemt_t`](#classregistry_1a09362dcb9bd021eadb89de3cda0e6eb8) | 

## Members

#### `public `[`entity_manager_t`](#classregistry_1_1entity__manager__t)` `[`entity_manager`](#classregistry_1a981a0c96d6eb81e70e595a5d450b558c) 

#### `public inline  `[`registry`](#classregistry_1a757883d504ab1bb5a06e0faa8e28664d)`()` 

#### `public inline  `[`~registry`](#classregistry_1a5007aa52f3b6809650467604be188acf)`()` 

#### `public template<>`  <br/>`inline `[`sparse_array`](#classsparse__array)`< Component > & `[`register_component`](#classregistry_1a19c4f7403bb0f2aa5f3f92f8b982fdb1)`()` 

#### `public template<>`  <br/>`inline `[`sparse_array`](#classsparse__array)`< Component > & `[`get_components`](#classregistry_1a99ec6244fa73ca7a6042048230a91e9a)`()` 

#### `public template<>`  <br/>`inline `[`sparse_array`](#classsparse__array)`< Component > const  & `[`get_components`](#classregistry_1ae35d18b5d8c07828cc5c55bc94f9f4f8)`() const` 

#### `public template<>`  <br/>`inline void `[`add_system`](#classregistry_1af9596641371a7191d44293d13c1f69bf)`(Function && f)` 

#### `public template<>`  <br/>`inline void `[`add_system`](#classregistry_1af7f9e3380b7c0c33223ace881609465e)`(Function & f)` 

#### `public inline void `[`run_systems`](#classregistry_1a1fda5cc52e611441228f8b1c26302060)`()` 

#### `public template<>`  <br/>`inline void `[`add_events_system`](#classregistry_1aad3a53aad49d662703ac8769ad0ad676)`(Function && f)` 

#### `public template<>`  <br/>`inline void `[`add_events_system`](#classregistry_1a6673f067ecfc396124759235cd32ebbb)`(Function & f)` 

#### `public inline void `[`run_events_systems`](#classregistry_1a842591a93878d83bd717f98b82bea2b3)`()` 

#### `typedef `[`entity_t`](#classregistry_1afbd442d3a10f483cd3caab2ded84bca2) 

#### `typedef `[`deleter_t`](#classregistry_1add498b246f43a27490a289380209237a) 

#### `typedef `[`systemt_t`](#classregistry_1a09362dcb9bd021eadb89de3cda0e6eb8) 

# class `sparse_array` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public inline  `[`sparse_array`](#classsparse__array_1a34c792f0a28f90cffd87e58c52f20017)`()` | 
`public inline  `[`sparse_array`](#classsparse__array_1a2530f93c4d5c88e06ba6c69b4e04ca40)`(`[`sparse_array`](#classsparse__array)` const & other)` | 
`public inline  `[`sparse_array`](#classsparse__array_1abce5f36fcd9fba0ef3ce5280cbe241db)`(`[`sparse_array`](#classsparse__array)` && other) noexcept` | 
`public inline  `[`~sparse_array`](#classsparse__array_1a4fcfd9065975ddcb90f2a84c91313867)`()` | 
`public inline `[`sparse_array`](#classsparse__array)` & `[`operator=`](#classsparse__array_1a0479eb52d1bec90c260bce70048b028c)`(`[`sparse_array`](#classsparse__array)` const & other)` | 
`public inline `[`sparse_array`](#classsparse__array)` & `[`operator=`](#classsparse__array_1a54c8c83c7eeff9f37c6b66440a51a21e)`(`[`sparse_array`](#classsparse__array)` && other) noexcept` | 
`public inline reference_type `[`operator[]`](#classsparse__array_1a4aa1f2fae14ff1cecdc6e42ded260cad)`(size_t idx)` | 
`public inline const_reference_type `[`operator[]`](#classsparse__array_1a1d66e1a1e11a9bcef70425c3c09eb6b4)`(size_t idx) const` | 
`public inline iterator `[`begin`](#classsparse__array_1a1cdf824b5897fb3ffc857843b37453b2)`()` | 
`public inline const_iterator `[`begin`](#classsparse__array_1a25c3a93f84f860ee55bb25f8da67e358)`() const` | 
`public inline const_iterator `[`cbegin`](#classsparse__array_1a8f6e23b67ea783baf53129f8907e297a)`() const` | 
`public inline iterator `[`end`](#classsparse__array_1af6749bdfbdc5200a77549f52594107eb)`()` | 
`public inline const_iterator `[`end`](#classsparse__array_1a094425cbf56a592e130b67ecda68cd3d)`() const` | 
`public inline const_iterator `[`cend`](#classsparse__array_1adb95eba3fb7e88207a4374c04950d167)`() const` | 
`public inline size_type `[`size`](#classsparse__array_1a6679a2315be266da4c01ad97f00e51fd)`() const` | 
`public inline bool `[`has_value_at`](#classsparse__array_1a2e2d04ac69bfebfa5cc7ac4525c91813)`(size_type pos) const` | 
`public inline reference_type `[`insert_at`](#classsparse__array_1a937a81f8dc37d0a33237f3442225695c)`(size_type pos,Component const & comp)` | 
`public inline reference_type `[`insert_at`](#classsparse__array_1a0deaa37276bdd7ed64b33ce2d5c91e94)`(size_type pos,Component && comp)` | 
`public template<>`  <br/>`inline reference_type `[`emplace_at`](#classsparse__array_1a198a17233acf70ec1d3d1451e77e12df)`(size_type pos,Params &&... params)` | 
`public inline void `[`erase`](#classsparse__array_1ac0bea77704ce39c1a731dc69de8d9d2d)`(size_type pos)` | 
`public inline size_type `[`get_index`](#classsparse__array_1acea541e416d26ee1fd0e7e5a8be7d989)`(value_type const & val) const` | 
`typedef `[`value_type`](#classsparse__array_1ab7403a6f935fa66034cce5bdcf49a9fc) | 
`typedef `[`reference_type`](#classsparse__array_1ae00c5b30838e89f0d368d55e0ba6a54d) | 
`typedef `[`const_reference_type`](#classsparse__array_1a373bf1a871a33e79a21da15acf3652f8) | 
`typedef `[`container_t`](#classsparse__array_1a5f747e93a9406474b106bde9c66f01b7) | 
`typedef `[`size_type`](#classsparse__array_1af1468a11a30a58090580d1fb399e3cc0) | 
`typedef `[`iterator`](#classsparse__array_1a1293c5b64d77bb97ed87e57c6276925e) | 
`typedef `[`const_iterator`](#classsparse__array_1a9beecc69673481f79844336194dfc1a2) | 

## Members

#### `public inline  `[`sparse_array`](#classsparse__array_1a34c792f0a28f90cffd87e58c52f20017)`()` 

#### `public inline  `[`sparse_array`](#classsparse__array_1a2530f93c4d5c88e06ba6c69b4e04ca40)`(`[`sparse_array`](#classsparse__array)` const & other)` 

#### `public inline  `[`sparse_array`](#classsparse__array_1abce5f36fcd9fba0ef3ce5280cbe241db)`(`[`sparse_array`](#classsparse__array)` && other) noexcept` 

#### `public inline  `[`~sparse_array`](#classsparse__array_1a4fcfd9065975ddcb90f2a84c91313867)`()` 

#### `public inline `[`sparse_array`](#classsparse__array)` & `[`operator=`](#classsparse__array_1a0479eb52d1bec90c260bce70048b028c)`(`[`sparse_array`](#classsparse__array)` const & other)` 

#### `public inline `[`sparse_array`](#classsparse__array)` & `[`operator=`](#classsparse__array_1a54c8c83c7eeff9f37c6b66440a51a21e)`(`[`sparse_array`](#classsparse__array)` && other) noexcept` 

#### `public inline reference_type `[`operator[]`](#classsparse__array_1a4aa1f2fae14ff1cecdc6e42ded260cad)`(size_t idx)` 

#### `public inline const_reference_type `[`operator[]`](#classsparse__array_1a1d66e1a1e11a9bcef70425c3c09eb6b4)`(size_t idx) const` 

#### `public inline iterator `[`begin`](#classsparse__array_1a1cdf824b5897fb3ffc857843b37453b2)`()` 

#### `public inline const_iterator `[`begin`](#classsparse__array_1a25c3a93f84f860ee55bb25f8da67e358)`() const` 

#### `public inline const_iterator `[`cbegin`](#classsparse__array_1a8f6e23b67ea783baf53129f8907e297a)`() const` 

#### `public inline iterator `[`end`](#classsparse__array_1af6749bdfbdc5200a77549f52594107eb)`()` 

#### `public inline const_iterator `[`end`](#classsparse__array_1a094425cbf56a592e130b67ecda68cd3d)`() const` 

#### `public inline const_iterator `[`cend`](#classsparse__array_1adb95eba3fb7e88207a4374c04950d167)`() const` 

#### `public inline size_type `[`size`](#classsparse__array_1a6679a2315be266da4c01ad97f00e51fd)`() const` 

#### `public inline bool `[`has_value_at`](#classsparse__array_1a2e2d04ac69bfebfa5cc7ac4525c91813)`(size_type pos) const` 

#### `public inline reference_type `[`insert_at`](#classsparse__array_1a937a81f8dc37d0a33237f3442225695c)`(size_type pos,Component const & comp)` 

#### `public inline reference_type `[`insert_at`](#classsparse__array_1a0deaa37276bdd7ed64b33ce2d5c91e94)`(size_type pos,Component && comp)` 

#### `public template<>`  <br/>`inline reference_type `[`emplace_at`](#classsparse__array_1a198a17233acf70ec1d3d1451e77e12df)`(size_type pos,Params &&... params)` 

#### `public inline void `[`erase`](#classsparse__array_1ac0bea77704ce39c1a731dc69de8d9d2d)`(size_type pos)` 

#### `public inline size_type `[`get_index`](#classsparse__array_1acea541e416d26ee1fd0e7e5a8be7d989)`(value_type const & val) const` 

#### `typedef `[`value_type`](#classsparse__array_1ab7403a6f935fa66034cce5bdcf49a9fc) 

#### `typedef `[`reference_type`](#classsparse__array_1ae00c5b30838e89f0d368d55e0ba6a54d) 

#### `typedef `[`const_reference_type`](#classsparse__array_1a373bf1a871a33e79a21da15acf3652f8) 

#### `typedef `[`container_t`](#classsparse__array_1a5f747e93a9406474b106bde9c66f01b7) 

#### `typedef `[`size_type`](#classsparse__array_1af1468a11a30a58090580d1fb399e3cc0) 

#### `typedef `[`iterator`](#classsparse__array_1a1293c5b64d77bb97ed87e57c6276925e) 

#### `typedef `[`const_iterator`](#classsparse__array_1a9beecc69673481f79844336194dfc1a2) 

# class `Test` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public int `[`a`](#classTest_1af0802b1f817c7baf4ec7dc214b81c909) | 
`public std::string `[`s`](#classTest_1a3973896fdcf5a9310602c4cffdfc1768) | 
`public std::vector< float > `[`v`](#classTest_1acd27ea3aef46e51b0664986315b92773) | 
`public inline  `[`Test`](#classTest_1a99f2bbfac6c95612322b0f10e607ebe5)`()` | 
`public inline  `[`Test`](#classTest_1a08807bbd5bfe2ab43e975644729e87a0)`(int i,std::string c,float f1,float f2)` | 
`public template<>`  <br/>`inline void `[`serialize`](#classTest_1af23c3a107c375bfba55174dfdb780709)`(Archive & ar,const unsigned int version)` | 

## Members

#### `public int `[`a`](#classTest_1af0802b1f817c7baf4ec7dc214b81c909) 

#### `public std::string `[`s`](#classTest_1a3973896fdcf5a9310602c4cffdfc1768) 

#### `public std::vector< float > `[`v`](#classTest_1acd27ea3aef46e51b0664986315b92773) 

#### `public inline  `[`Test`](#classTest_1a99f2bbfac6c95612322b0f10e607ebe5)`()` 

#### `public inline  `[`Test`](#classTest_1a08807bbd5bfe2ab43e975644729e87a0)`(int i,std::string c,float f1,float f2)` 

#### `public template<>`  <br/>`inline void `[`serialize`](#classTest_1af23c3a107c375bfba55174dfdb780709)`(Archive & ar,const unsigned int version)` 

# struct `Vector2D` 

## Summary

 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
`public T `[`x`](#structVector2D_1a65e391ec61c185092a02cf6301d0fff7) | 
`public T `[`y`](#structVector2D_1a6a91fccbbd37162d28fa54aeeb88f9d2) | 
`public inline  `[`Vector2D`](#structVector2D_1ab0c331c7e7c41bc297447fc9de7aa682)`(T _x,T _y)` | 

## Members

#### `public T `[`x`](#structVector2D_1a65e391ec61c185092a02cf6301d0fff7) 

#### `public T `[`y`](#structVector2D_1a6a91fccbbd37162d28fa54aeeb88f9d2) 

#### `public inline  `[`Vector2D`](#structVector2D_1ab0c331c7e7c41bc297447fc9de7aa682)`(T _x,T _y)` 

Generated by [Moxygen](https://sourcey.com/moxygen)