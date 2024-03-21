<script>
    import { Input, Label, Button, P } from 'flowbite-svelte';
</script>

<div class="flex flex-col h-screen justify-center items-center mx-4 space-y-4">
    <div>
        <P size="3xl" weight="semibold">Demo</P>
    </div>
    <div class="w-full max-w-md border rounded-lg bg-gray-800 border-gray-700">
        <div class="mt-4 mb-6 mx-4">
            <P size="xl" weight="semibold">Sign in</P>
        </div>
        <form action="" class="m-4">
            <div class="mb-6">
                <Label class="mb-2">Email</Label>
                <Input type="text" placeholder="Email" size="lg"></Input>
            </div>
            <div class="mb-8">
                <Label class="mb-2">Passwort</Label>
                <Input type="password" placeholder="Passwort" size="lg"></Input>
            </div>
            <Button type="submit" class="w-full mb-4" size="lg">Sign in</Button>
        </form>
    </div>
</div>

