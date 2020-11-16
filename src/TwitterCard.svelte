<script>
  export let profilePhoto;
  export let coverPhoto;
  export let name;
  export let handler;
  export let bio;
  export let location;
  export let joinedDate;
  export let birthday;
  export let followersCount;
  export let followingCount;
</script>

<div class="border m-4">
  <img src={coverPhoto} alt="cover" class="w-full" />
  <img
    src={profilePhoto}
    alt="profile"
    class="h-32 w-32 rounded-full p-1 -mt-16 ml-4 bg-white inline-block" />

  <div class="ml-4">
    <div class="flex flex-col">
      <span class="text-lg font-bold">{name}</span>
      <span class="text-gray-500 -mt-1">{handler}</span>
    </div>

    <div class="my-2">{bio}</div>

    <div class="flex mb-2">
      <div class="flex mr-4 text-gray-500">
        <svg
          class="h-6 w-6 inline mr-1"
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor">
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z" />
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M15 11a3 3 0 11-6 0 3 3 0 016 0z" />
        </svg>
        <span>{location}</span>
      </div>
      <div class="flex text-gray-500 mr-4">
        <svg
          class="h-6 w-6 inline mr-1"
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor">
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M21 15.546c-.523 0-1.046.151-1.5.454a2.704 2.704 0 01-3 0 2.704 2.704 0 00-3 0 2.704 2.704 0 01-3 0 2.704 2.704 0 00-3 0 2.704 2.704 0 01-3 0 2.701 2.701 0 00-1.5-.454M9 6v2m3-2v2m3-2v2M9 3h.01M12 3h.01M15 3h.01M21 21v-7a2 2 0 00-2-2H5a2 2 0 00-2 2v7h18zm-3-9v-2a2 2 0 00-2-2H8a2 2 0 00-2 2v2h12z" />
        </svg>

        <span>Born {birthday}</span>
      </div>
      <div class="flex text-gray-500 mr-4">
        <svg
          class="h-6 w-6 inline mr-1"
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor">
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z" />
        </svg>
        <span>Joined {joinedDate}</span>
      </div>
    </div>

    <div class="mb-2 flex">
      <div class="flex mr-4">
        <span class="font-bold mr-1">{followingCount}</span>
        <span class="text-gray-600">Following</span>
      </div>
      <div class="flex">
        <span class="font-bold mr-1">{followersCount}</span>
        <span class="text-gray-600">Followers</span>
      </div>
    </div>
  </div>
</div>
