/**
 * BetterDiscord Material Design Icon
 * Copyright (c) 2015-present Jiiks/JsSucks - https://github.com/Jiiks / https://github.com/JsSucks
 * All rights reserved.
 * https://betterdiscord.net
 *
 * This source code is licensed under the MIT license found in the
 * LICENSE file in the root directory of this source tree.
 *
 * Material Design Icons
 * Copyright (c) 2014 Google
 * Apache 2.0 LICENSE
 * https://www.apache.org/licenses/LICENSE-2.0.txt
*/

<template>
    <span class="bd-materialDesignIcon">
        <svg :width="size || 24" :height="size || 24" viewBox="0 0 24 24">
            <path d="M 19.9994,11.9981C 19.9994,16.4161 16.4174,19.9981 11.9994,19.9981C 7.58139,19.9981 3.99939,16.4161 3.99939,11.9981C 3.99939,7.58007 7.58139,3.99807 11.9994,3.99807C 12.7634,3.99807 13.5004,4.11207 14.2004,4.31207L 15.7724,2.74007C 14.6074,2.26467 13.3354,1.99807 11.9994,1.99807C 6.47638,1.99807 1.99939,6.47507 1.99939,11.9981C 1.99939,17.5211 6.47638,21.9981 11.9994,21.9981C 17.5224,21.9981 21.9994,17.5211 21.9994,11.9981M 7.91339,10.0841L 6.49939,11.4981L 10.9994,15.9981L 20.9994,5.99807L 19.5854,4.58407L 10.9994,13.1701L 7.91339,10.0841 Z " />
        </svg>
    </span>
</template>
<script>
    export default {
        props: ['size']
    }
</script>
