<template>
  <div class="home">
    <div class="component component-1">
      <p class="head">Salary Range</p>
      <div class="details">
        <select class="select" name="min" id="">
          <option value="Min">Min</option>
          <option value="Min">Min</option>
          <option value="Min">Min</option>
          <option value="Min">Min</option>
        </select>
        <select class="select" name="max" id="">
          <option value="Min">Max</option>
        </select>
        <button class="btn btn-apply">Apply</button>
      </div>
    </div>
    <div class="component component-2">
      <p class="head">Location</p>
      <div class="details">
        <input type="text" class="input-text" placeholder="Enter Location" />
        <div class="checkbox-area">
          <input class="check-input" type="checkbox" />
          <label for="checkbox1">Remote Position</label>
        </div>
        <div class="checkbox-area">
          <input class="check-input" type="checkbox" />
          <label for="checkbox1">On Site Position</label>
        </div>
      </div>
    </div>
    <div class="component component-3">
      <p class="head">Experience Level</p>
      <div class="details">
        <div class="tag tag-1">
          <div class="checkbox-area">
            <input class="check-input" type="checkbox" />
            <label for="checkbox1">No Experience</label>
          </div>
          <div class="checkbox-area">
            <input class="check-input" type="checkbox" />
            <label for="checkbox1">3-5 Years</label>
          </div>
        </div>
        <div class="tag tag-2">
          <div class="checkbox-area">
            <input class="check-input" type="checkbox" />
            <label for="checkbox1">1-2 Years</label>
          </div>
          <div class="checkbox-area">
            <input class="check-input" type="checkbox" />
            <label for="checkbox1">6+ Years</label>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
};
</script>
<style lang="scss" scoped>
$text-color: #d0cae5;
$button-color: #d24f7d;
.home {
  padding: 15px 0px;
  width: 100%;
  min-height: 100vh;
  padding: 10px;
  background: #241f34;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
.component {
  background: #2a243d;
  margin-bottom: 20px;
  padding: 45px 55px;
  border-radius: 10px;
  box-shadow: 4px 8px 6px rgba(0, 0, 0, 0.3);
}
.head {
  color: $text-color;
  font-size: 22px;
  line-height: 28px;
  margin-bottom: 20px;
}
.btn {
  border: none;
  color: white;
}
.select {
  border: 1px solid #453d5e;
  color: white;

  &:focus {
    border: 1px solid #8364e6;
  }
  option {
    background: #241f34;
    border: none;
  }
}

.checkbox-area {
  margin: 15px 0px;
  display: flex;
  align-items: center;
  label {
    font-size: 16px;
    color: $text-color;
    line-height: 20px;
  }
  .check-input {
    background: transparent;
    padding: 6px;
    height: 25px;
    width: 25px;
    margin-right: 25px;
    border: 1x solid #453d5e;
    color: #241f34;
    appearance: none;
    border: 1px solid #34495e;
    border-radius: 4px;
    outline: none;
    transition-duration: 0.3s;
    background-color: transparent;
    cursor: pointer;

    &:checked {
      background: #0c0329;
    }
  }
}
.component-1 {
  text-align: start;
  display: flex;
  flex-direction: column;
  justify-content: space-around;
  .details {
    display: flex;
    justify-content: center;
    background: transparent;
    select {
      background: inherit;
      width: 150px;
      height: 56px;
      border-radius: 5px;
      margin-right: 20px;
    }
    .btn-apply {
      background: #d24f7d;
      padding: 20px 36px;
      border-radius: 5px;
    }
  }
}
.component-2 {
  text-align: start;
  .details {
    display: flex;
    background: transparent;
    flex-direction: column;
  }
  .input-text {
    background: inherit;
    border: 1px solid #453d5e;
    border-radius: 10px;
    padding: 20px 25px;
    color: white;
    &:focus {
      outline: none;
    }
  }
}

.component-3 {
  text-align: start;
  .details {
    display: flex;
    flex-direction: column;
    justify-content: center;
    .tag {
      display: flex;
      .checkbox-area {
        margin-bottom: 30px;
        margin-right:30px ;
      }
    }
  }
}

@media screen and (max-width: 640px) {
  .component{
    padding: 15px;
  }
  .component-1 {
    .details {
      display: flex;
      flex-wrap: wrap;
      align-items: start;
      justify-content: start;
      select{
          width: 120px;
      }
    }

  }
  .component-3 {
    .tag {
      .checkbox-area {
        margin: 5px;
      }
    }
  }
}
</style>