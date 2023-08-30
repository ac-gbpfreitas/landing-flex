<template>
    <section class="row contact" id="contact">
        <article>
            <h2>
                Contact
            </h2>
            <p>
                SEND A MESSAGE TO US
            </p>
        </article>
        <section>
            <article>
                <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Sapiente modi debitis illo, autem magnam, iure odit ipsum quae, porro unde repudiandae voluptas cum. Eligendi a repellendus at vero fuga possimus iure! Alias fugiat quo nesciunt.
                </p>
                <p>
                    Lorem ipsum dolor sit, amet consectetur adipisicing elit. Temporibus, dicta impedit! Iure expedita aliquam ipsa reiciendis magnam natus recusandae modi molestias autem eum placeat aut, voluptatibus, temporibus adipisci porro quia.
                </p>
                <p>
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Totam sequi, delectus maiores aperiam nostrum id, omnis quisquam, ratione dicta adipisci a quo cumque provident optio.
                </p>
                <ul>
                    <li>
                        Phone: 033-033-0660
                    </li>
                    <li>
                        Email:
                        <a href="mailto:info@company.com">
                            info@company.com
                        </a>
                    </li>
                    <li>
                        Address:
                        <address>
                            880 De Best Studio, Fork Street, San Francisco
                        </address>
                    </li>
                </ul>
            </article>
            <section>
                <form action="#">
                    <input type="text" name="name" id="name" placeholder="Your Name">
                    <input type="email" name="email" id="email" placeholder="Your Email">
                    <input type="text" name="subject" id="subject" placeholder="Subject">
                    <textarea name="message" id="message" placeholder="Message"></textarea>
                    <input type="submit" value="SEND MESSAGE">
                </form>
            </section>
        </section>
    </section>
</template>

<script>
export default {
    name: "ContactComponent"
}
</script>