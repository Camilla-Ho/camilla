<template>
    <div>
        <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
            <a href="" class="navbar-brand h1">工作室</a>
            <button class="navbar-toggler" data-toggle="collapse" data-target="#mynav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="mynav">
                <ul class="navbar-nav mr-auto">
                    <li class="nav-item"><a href="" class="nav-link active">免費刊登廣告</a></li>
                    <li class="nav-item"><a href="" class="nav-link">登入</a></li>
                    <li class="nav-item"><a href="" class="nav-link">註冊</a></li>
                </ul>
                <form action="" class="form-inline">
                    <input type="text" class="form-control mr-2" placeholder="search">
                    <button class="btn btn-primary">Search</button>
                </form>
            </div>
        </nav>

        <div class="jumbotron jumbotron-fluid">
            <div class="container">
                <h1>Headar Iamge</h1>
                <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Nam laboriosam, nostrum numquam dolore excepturi quaerat ipsa consequuntur. Necessitatibus numquam consequuntur voluptatem rem, quos vitae cupiditate enim fugiat ab illum sapiente.</p>
                <a href="" class="btn btn-primary">申請</a>
            </div>
        </div>

        <div class="container">
            <div class="row">
                <div class="col-lg-12 card">
                    <div class="card-body">
                        <h2>Section1</h2>
                        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. </p>
                        <a href="" class="btn btn-primary">GO</a>
                    </div>
                </div>

                <div class="col-lg-6 card mt-2">
                    <div class="card-body">
                        <h2>Section1</h2>
                        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. </p>
                        <a href="" class="btn btn-primary">GO</a>
                    </div>
                </div>
                <div class="col-lg-6 card mt-2">
                    <div class="card-body">
                        <h2>Section2</h2>
                        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. </p>
                        <a href="" class="btn btn-primary">GO</a>
                    </div>
                </div>

                <div class="col-lg-4 card mt-2">
                    <div class="card-body">
                        <h2>Section1</h2>
                        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. </p>
                        <a href="" class="btn btn-primary">GO</a>
                    </div>
                </div>
                <div class="col-lg-4 card mt-2">
                    <div class="card-body">
                        <h2>Section2</h2>
                        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. </p>
                        <a href="" class="btn btn-primary">GO</a>
                    </div>
                </div>
                <div class="col-lg-4 card mt-2">
                    <div class="card-body">
                        <h2>Section3</h2>
                        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. </p>
                        <a href="" class="btn btn-primary">GO</a>
                    </div>
                </div>

                <div class="col-lg-3 card mt-2">
                    <div class="card-body">
                        <h2>Section1</h2>
                        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. </p>
                        <a href="" class="btn btn-primary">GO</a>
                    </div>
                </div>
                <div class="col-lg-3 card mt-2">
                    <div class="card-body">
                        <h2>Section2</h2>
                        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit.</p>
                        <a href="" class="btn btn-primary">GO</a>
                    </div>
                </div>
                <div class="col-lg-3 card mt-2">
                    <div class="card-body">
                        <h2>Section3</h2>
                        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit.</p>
                        <a href="" class="btn btn-primary">GO</a>
                    </div>
                </div>
                <div class="col-lg-3 card mt-2">
                    <div class="card-body">
                        <h2>Section4</h2>
                        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit.</p>
                        <a href="" class="btn btn-primary">GO</a>
                    </div>
                </div>
            </div>

            <hr>
            <footer class="text-center text-muted">
                <p>&copy; 2020 工作室.</p>
            </footer>
        </div>

    </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.jumbotron {
    background-image: url("https://cdn.pixabay.com/photo/2020/07/01/17/56/chamomile-5360418_1280.jpg");
    background-size: cover;
    color: #fff;
}
</style>
